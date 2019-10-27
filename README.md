page_dewarp
===========

## Modified

This fork has been modified to work with:
 - python 3
 - updates to opencv
 - used for vertical line detection instead of horizontal text detection

Page dewarping and thresholding using a "cubic sheet" model - see full writeup at <https://mzucker.github.io/2016/08/15/page-dewarping.html>

Requirements:

 - scipy
 - OpenCV 3.0 or greater
 - Image module from PIL or Pillow
 
Usage:

    page_dewarp.py IMAGE1 [IMAGE2 ...]
