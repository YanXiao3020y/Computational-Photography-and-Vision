**Overview**

The assignment involves developing a face morphing and swapping system
using piecewise affine warping. The first task is to create a function
for computing affine transformations between triangles and applying
these transformations to warp images. This involves generating a
transformation matrix that maps one triangle to another and applying
this transformation to a set of points. The next step is to implement
piecewise affine warping by determining which triangle each pixel falls
into, computing the affine transformations for each triangle, and using
bilinear interpolation to warp the image. For face morphing, the
keypoints from two face images are used to generate a sequence of
intermediate images transitioning from one face to the other, blending
both images. For face swapping, the face from one image is warped and
composited into the second image using an alpha map to manage blending
and minimize artifacts.


### More Info
For additional details, please refer to the 5_faceswap.ipynb.