## JupiterStorms

### [The Storms of Jupiter](https://github.com/amnh/HackTheSolarSystem/wiki/The-Storms-of-Jupiter)

### Created by Team T.E.N
* Tuba Opel (tsopel)
* Eric Cheng (ericcheng95)
* Nancy Wen (nwen2011)

### Solution Description

1) Storm Detection:
First step was to apply a Gaussian Blur onto the image, this reduced the noise in the image and made it easier to detect shapes and blobs. Then the Hough Circle Detection algorithm was applied onto the blurred image.

2) Collect metrics of different Storms relative to the Great Red Spot


### Installation Instructions

1) Storm Detection:
To run, install Anaconda-Navigator https://anaconda.org/anaconda/anaconda-navigator and OpenCV. Open Anaconda-Navigator and click on Jupyter Notebook, this will open a webpage where you can see a list of folders/files. Navigate to where the jupiter-storm-detection.ipynb file is and click on it. This should open a new page where you can see the source code.
In the second section of this page, you can set the file path of the images you want to detect. To compile the section, just hit shift-enter. You will need to do this for each section consecutively. There should be 4 sections: 1. for importing libraries, 2. for storing image filepaths, 3. for processing the images, and 4. for calling the function in section 3.
