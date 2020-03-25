[![Launch in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ma-riviere/IP101.git/master)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# IP101: Image Processing with Python and Jupyter Notebooks

## 1. Introduction:
 * Manipulating image files
 * Drawing on images & masking
 * Basic transformations: cropping, affine transformations, rotations, ...


## 2. Gray level manipulation: 
 * Introduction to Histograms
 * Exposition & Contrast
 * Linear transformations: contrast stretching & equalization
 * Non-linear transformations: log and gamma transforms


## 3. Noise & Morphological operations:
 * Noise types & denoising
 * Erosions & Dilations
 * Opening & Closing
 * Hit-and-Miss
 * Thinning & Thickening
 * Skeletonization
 * Convex Hull


## 4. Filtering and Convolutions:
 * Introduction to Fourier Transform, filtering & convolutions
 * Smoothing / low-pass filtering: average, median and Gaussian filters
 * Sharpening / high-pass filtering: Prewitt, Sobel, Laplace & Canny filters


## 5. Segmentation:
 * Simple Thresholding methods: Global thresholding, Otsu's method, Adaptative Thresholding
 * Unsupervised segmentation: Mean-Shift, Watershed, SuperPixels, Region Adjacency Graph


***
# IP101: Setup

## 1. To execute locally:
 * Download or clone this repo
 * Install the requirements (`pip install -r requirements.txt`)
 * Open console in repo and start Jupyter (`jupyter notebook` command)
 
## 2. To execute on Colab:
 * Copy or clone the repo to Colab
 * Open Notebook file (`.ipynb`) with Google Colab (install the Google Drive addon if required)
 * Install missing dependencies with `!pip install` in one of the notebook's cells
 

### ~ Enjoy !


# Licence

Copyright © 2020 Rivière Marc-Aurèle

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
