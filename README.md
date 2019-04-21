# SR_RemoteSensing

Super-Resolution (SR) deep learning models supporting remote sensing data (.tif)

*_The project is still ongoing and this repository will keep updating. If for any reason that the code doesn't work, feel free to ask._

The code used here is based on [this](https://github.com/xinntao/BasicSR) repository. Please check to get more detailed information. 
I just extended their work by supporting .tif and x3 model initializing with pretrained weights from x4 model.

Our work is using Sentinel-10m data and Landsat-30m data to generate SR Landsat-10m data.

tiff-read.ipynb is for data preparation, train-val-test data spliting and format transformation. 
