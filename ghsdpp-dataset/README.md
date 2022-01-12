# GHS-DPP dataset (av1 compressed)

This dataset contains the GHS-DPP recordings
of \emph{Drosophila} wild-type and \emph{spam} and 
honeybee compound eyes.
It shows how the rhabdomeres (or rhabdoms in honeybees) move
during the photoreceptor microsaccades, which are caused by
photomechanically contracting microvilli.

The original dataset consists of uncompressed 16-bit grayscale tiff images.
To make it more accessible, we have used the [AOMedia Video 1 (AV1)](https://en.wikipedia.org/wiki/AV1)
video compression algorithm (150 G -> 1.5 G).

## Details

Experimental details are presented in [the paper preprint](https://www.biorxiv.org/content/10.1101/2021.07.22.453335v2).
Shortly, the high-speed camera starts to acquire
images at 100 Hz, and simultaneously to this the stimulus UV LED turns on for 200 ms.
Then, the imaging is repeated in ~200 other eye locations (fullscans) or
repeated in the same location in total 25 times (manyrepeats).

For \emph{Drosophila} data

- time between frames: 10 ms
- pixel size: 0.817 µm/pixel


## Notes

Gonio Analysis v0.6.0 cannot yet directly work with av1 videos.
Temporary workaround is to convert the videos into tiff stacks.

Similarly, other software (ImageJ/Fiji) may require conversion to
other formats.

