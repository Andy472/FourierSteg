## Summary
A research proof of concept showing the viability of Fourier representation to be used in image steganography. Payloads are converted to binary and encoded pixel by pixel RGB bit by bit. Reed-Solomon error correction is applied to try and reduce effects of noise.


## File usage
| File | Usage |
|--|--|
| 1) CombinedGUI | Main program with UI |
| 2) CombinedEncode | Older encoding version |
| 3) CombinedDecode | Older decoding version  |
| 4) ConvDecoder| Take the inverse Fourier of 2 separate images of phase and magnitude that can be edited outside the program  |

The CombinedGUI is the main program and can be directly ran to present a UI allowing both encoding and decoding of images.

## Dependencies
Can be installed the usual way with "pip install name"
 - numpy
 - pillow
 - pypng
 - reedsolo
