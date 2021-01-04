# ImagetoCartoon
**This project aims at converting a regular image into its cartoon version.**

## Libraries used:
*Opencv
*Numpy
*Files in google.colab libraries

### Task list
- [x] Edge detection
- [x] Noise reduction
- [x] Color quantization
- [] Bilateral Filter
- [] bitwise_and

### Procedure
First the edges are detected and given a certain thickness. The blur is added to reduce the noise involved in the image. Using K-means algorithm we color quantize so that there are only certain number of colors available and not all unlike a real image. Since the cartoons are more of a uniform color base this is done.
