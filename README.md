# Corner-Detection
Building a computer vision algorithm from scratch which can detect corners which could be further used for used in motion detection, image registration, video tracking, panorama stitching, 3D reconstruction and object recognition.

## Algorithm built --> Harris Corner Detection
The first step includes defining the filters or kernels to be used which were mainly Sobel-x and y and the Gaussian kernels. Then defining the convolutionn function was the next step.
Now as for the Algorithm,
Harris Corner Algorithm is based on the equation ;

output = det(M) - k*trace^2

![hcd](https://github.com/K-Tanishq/Corner-Detection/assets/169484818/f4e2167a-7489-4750-98bc-8d82574cc5c4)

![harris](https://github.com/K-Tanishq/Corner-Detection/assets/169484818/8fa46b71-bd94-4ee4-8043-ab6d7608294e)

All values like Ix^2, Ix.Iy etc. all are calculated in this manner.

where, trace = Ix^2 + Iy^2 & det = Ix^2*Iy^2 -(IxIy)^2

if this output value is above a set threshold then that point is defined as corner.

## Sample Outputs

![1](https://github.com/K-Tanishq/Corner-Detection/assets/169484818/1428db41-3134-4f6c-8203-b9492d0634a9)
![2](https://github.com/K-Tanishq/Corner-Detection/assets/169484818/a610a469-43c7-41e8-82d4-591d8ed1f4e4)
![3](https://github.com/K-Tanishq/Corner-Detection/assets/169484818/c1e8fc54-57e7-4887-b808-37abcaa17540)
![4](https://github.com/K-Tanishq/Corner-Detection/assets/169484818/5aacf4b5-9924-43e4-a29a-27d20e517832)
