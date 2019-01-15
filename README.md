# SR_RemoteSensing

Super-Resolution (SR) deep learning models supporting remote sensing data (.tif)

The code used here is based on [this](https://github.com/xinntao/BasicSR) repository. Please check to get more detailed information. 
I just extend their work by supporting .tif and being able to extract pretrained weights from x4 model as initialized weights for x3 model.

Our work is using Sentinel-10m data and Landsat-30m data to generate SR Landsat-10m data.

tiff-read.ipynb is for data preparation, train-val-test data spliting and format transformation. 
