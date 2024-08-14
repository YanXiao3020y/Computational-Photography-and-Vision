**Overview**

The assignment involves developing an object detection system using
gradient-based features and sliding window classification. It begins
with computing and visualizing image gradients. Next, Histograms of
Oriented Gradients (HOG) are calculated for 8x8 pixel blocks, followed
by normalization and visualization of these histograms. Detection is
achieved by correlating a HOG template with an image's HOG feature map
and implementing non-maxima suppression to refine the results. Finally,
a function is created to learn and refine object templates by averaging
HOG features from positive and negative examples.

### More Info
For additional details, please refer to the 4_detection.ipynb.