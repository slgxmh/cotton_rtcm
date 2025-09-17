# cutton_rtcm

## Dataset

Download URL: https://1drv.ms/u/c/74e16ea964806b36/EWCRiUgD-iNNsKzfxJbftuwBovPWC0GFORP33besIDbxMg

This HDF5 file contains the following three parts of datasets:
- `images`: Transformed and enhanced image data.
  - **Dimensions**: `(N, 3, 224, 224)`
  - **Type**: `float32`
  - `N` is the total number of samples under this band.
- `de_labels`: Corresponding first label.
  - **Dimensions**: `(N,)`- **Type**: `int8`
- `ba_labels`: Corresponding second label.
  - **Dimensions**: `(N,)`
  - **Type**: `int8`
