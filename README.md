# ImagetoCartoon
**This project aims at converting a regular image into its cartoon version.**

## Libraries used:
- *Opencv
- *Numpy
- *Files in google.colab libraries

### Task list
- [x] Edge detection
- [x] Noise reduction
- [x] Color quantization
- [x] Bilateral Filter
- [x] bitwise_and
- [x] Dilation

### Procedure
First the edges are detected and given a certain thickness. The blur is added using medianblur() to reduce the salt-and-pepper noise involved in the image. Using K-means algorithm we color quantize so that there are only certain number of colors available and not all unlike a real image. Since the cartoons are more of a uniform color base this is done. This can be done with just the Bilateral+Blur+Edges or Quantization+Blur+Edges. Further the unwanted edges ,that is, the tiny lines that are not part of the large edge is removed by applying the morphological transformation, i.e, Dilation of the image.
