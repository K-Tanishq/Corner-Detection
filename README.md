# Corner-Detection
Building a computer vision algorithm from scratch which can detect corners which could be further used for used in motion detection, image registration, video tracking, panorama stitching, 3D reconstruction and object recognition.

## Algorithm built --> Harris Corner Detection
The first step includes defining the filters or kernels to be used which were mainly Sobel-x and y and the Gaussian kernels. Then defining the convolutionn function was the next step.
Now as for the Algorithm,
Harris Corner Algorithm is based on the equation ;

output = det(M) - k*trace^2
where, trace = Ix^2 + Iy^2 & det = Ix^2*Iy^2 -(IxIy)^2

if this output value is above a set threshold then that point is defined as corner.
