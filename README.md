# Stereo_matching
Convolutional Neural Network to to Estimate Depth


## Summary

Consider the following problem: given two images taken by cameras at different horizontal positions.The goal is to compare images pixel by pixel and find dipairity between pixels. Which will give the depth from focal point of images.


## Background


Depth image can be used eg for:
* Creating special effect for varoius image editing programs
* Can be used in computer vision for esitmation on size and distance of objects
* etc.


## How is it used?

User takes stereo images with camera in two different horizontal positions. Then images are analysed in cnn and result is created as anaglyph stereo image.



## Data sources and AI methods
KITTI Stereo Data Set is used for analysis. Tensorflow frmwork is used for training neural network

## Challenges
This project cann not be used for automotive and military purpose. It is not useful for measuring of true dispance.

## What next?

Ultimately this project would be useful of generating funny cat pictures.


## Acknowledgments

* Stereo Matching by Training a Convolutional Neural
Network to Compare Image Patches https://www.jmlr.org/papers/volume17/15-535/15-535.pdf
* Usings CNNs to Estimate Depth from Stereo
Imagery https://web.stanford.edu/class/ee368/Project_Autumn_1516/Reports/Jordan_Shridhar.pdf
* Computing the Stereo Matching Cost with a Convolutional Neural Network
 https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Zbontar_Computing_the_Stereo_2015_CVPR_paper.pdf
