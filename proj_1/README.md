## Hybrid Images
### Working Principle
* It works by the addition of a low frequency image and high freq image, and resultant
hybrid image is perceived as any of the individual image according to viewing distance.
* Both images should be of similar size like monroe and einstein imge. The image with more
pattern is chosen tobe high frequency image.
* When viewed nearer, humans want to perceive recognizable pattern. So recognize these
patterns.
* But the further we move away from hybrid, the more difficult it is to recognise these patterns.
So after a certain distance the brain recognises the background image.

<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_1/output_1/1_a.PNG?raw=true" width=100% alt="original pics">
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_1/output_1/1_b.PNG?raw=true" width=100% alt="fft pics">

## Pyramid Image
### Working Principle
1. At each layer of the pyramid, Gaussian is suppressing high frequency components in the image which are responsible for finer texture. 
2. On the other hand since when we are subtracting the gaussian upsampled image from original image we are selecting the high frequency components in image and storing them as a Laplacian image.
3. If we see the fft output of both laplacian and gaussian images, we can clearly see that, center pixels of gaussins fft are much brighter than the fft of laplacian, indicating that gaussin is selecting lower frequency.
4. Similarly the fft of gaussian near the edges which is responsible for high frequencies is darker than the laplacian fft since laplacian is selecting those higher frequencies.
<div align="center">


  <h4 align="center"> Gaussian pyramid (level - 5)</h4>


</div>
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_1/output_1/2_gaus.PNG?raw=true" width=100% alt="gaus">
<div align="center">


  <h4 align="center"> Laplacian pyramid (level - 5)</h4>


</div>
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_1/output_1/2_lap.PNG?raw=true" width=100% alt="lap">

## Edge Detection

## Template Matching
