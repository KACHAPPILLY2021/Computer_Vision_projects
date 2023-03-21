<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">


  <h1 align="center">First Principles of Computer Vision</h1>


</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary><h3>Table of Contents</h3></summary>
  <ol>
    <li><a href="#about-the-repository">About The Repository</a></li>
    <li>
      <a href="#project-1">Project 1</a>
      <ul>
        <li><a href="#hybrid-images">Hybrid Images</a></li>
      </ul>
      <ul>
        <li><a href="#pyramid-image">Pyramid Image</a></li>
      </ul>
      <ul>
        <li><a href="#edge-detection">Edge Detection</a></li>
      </ul>
      <ul>
        <li><a href="#template-matching">Template Matching</a></li>
      </ul>
    </li>
    <li>
      <a href="#project-2">Project 2</a>
      <ul>
        <li><a href="#feature-tracker">Feature Tracker</a></li>
      </ul>
      <ul>
        <li><a href="#shape-alignment">Shape Alignment</a></li>
      </ul>
      <ul>
        <li><a href="#object-instance-recognition">Object Instance Recognition</a></li>
      </ul>
    </li>
    <li>
      <a href="#project-3">Project 3</a>
      <ul>
        <li><a href="#epipolar-geometry">Epipolar Geometry</a></li>
      </ul>
      <ul>
        <li><a href="#image-stitching">Image Stitching</a></li>
      </ul>
      <ul>
        <li><a href="#affine-structure-from-motion">Affine Structure from Motion</a></li>
      </ul>
    </li>
    <li>
      <a href="#project-4">Project 4</a>
      <ul>
        <li><a href="#slic-superpixels">SLIC Superpixels</a></li>
      </ul>
      <ul>
        <li><a href="#graphcut-segmentation">Graphcut Segmentation</a></li>
      </ul>
    </li>
    <li>
      <a href="#project-5">Project 5</a>
      <ul>
        <li><a href="#basic-backpropagation-in-neural-network">Basic Backpropagation in Neural Network</a></li>
      </ul>
      <ul>
        <li><a href="#image-classification-using-cnn">Image Classification using CNN</a></li>
      </ul>
      <ul>
        <li><a href="#semantic-segmentation-using-fcn-32">Semantic Segmentation using FCN 32</a></li>
      </ul>
    </li>
    <li>
      <a <a href="#prerequisites">Prerequisites</a>
    </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>



<!-- ABOUT THE REPO -->
## About The Repository



This repository contains all the projects that I implemented for my graduate course : Computer Processing of Pictorial Information.
All major Computer Vision concepts implemented here were developed from scratch ```without``` utilizing ```OpenCV's built-in``` functions.

Below are the outputs for each project and their associated links to view them.
Use ```Table of Contents``` for easy navigation through projects.

```DISCLAIMER``` : Please note that in the future, the input data may no longer be accessible as it was obtained from the university server.



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Project1 -->
## Project 1

### Hybrid Images | Image Pyramids | Edge Detection | Template Matching

The outputs for this project is as follows:

### Hybrid Images
* A hybrid image is the sum of a low-pass filtered version of the one image and a high-pass filtered
version of a second image by making use of FFT.

* Einstein and Marlyn Monroe hybrid image
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_1/output_1/1_main.PNG?raw=true" width=75% alt="hybrid">

### Pyramid Image
* Gaussian and Laplacian pyramid of level 5 implemented, followed by image reconstruction.

Original Image | Reconstructed Image
:-------------------------:|:-------------------------:
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_1/texture.jpg?raw=true" width=40% alt="original"> | <img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_1/output_1/2_main.PNG?raw=true" width=30% alt="reconstructed">

### Edge Detection
* Computed the boundary magnitude and orientation using a set of oriented filters, such as elongated Gaussian derivative filters. Followed by non maxima suppression of the soft boundary map.
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_1/output_1/3_main.PNG?raw=true" width=100% alt="hybrid">

### Template Matching
* Matched template for a given map by implementing Sum of Squared Differences.
* Puzzle Piece to find
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_1/output_1/4_waldo.PNG?raw=true" width=10% alt="hybrid">

* Waldo identified in Map
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_1/output_1/4_puzzle.PNG?raw=true" width=50% alt="hybrid">

[CLICK HERE](https://github.com/KACHAPPILLY2021/Computer_Vision_projects/tree/main/proj_1#readme) - To view detailed project
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Project2 -->
## Project 2

### Feature Tracker | Shape Alignment | Object Instance Recognition

The outputs for this project is as follows:

### Feature Tracker
Corners Detector | Optical Flow
:-------------------------:|:-------------------------:
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_2/output_2/1_main_harris.PNG?raw=true" width=100% alt="harris"> | <img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_2/output_2/1_main_flow.PNG?raw=true" width=100% alt="optical flow">

### Shape Alignment
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_2/output_2/2_main.PNG?raw=true" width=100% alt="shape">

### Object Instance Recognition
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_2/output_2/3_main.PNG?raw=true" width=70% alt="sift">

[CLICK HERE](https://github.com/KACHAPPILLY2021/Computer_Vision_projects/tree/main/proj_2) - To view detailed project
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Project3 -->
## Project 3

### Epipolar Geometry | Image Stitching | Structure from Motion

The outputs for this project is as follows:

### Epipolar Geometry
Image 1 | Image 2
:-------------------------:|:-------------------------:
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_3/output_3/1_img1.PNG?raw=true" width=100% alt="epi1"> | <img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_3/output_3/1_img2.PNG?raw=true" width=100% alt="epi2">

### Image Stitching
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_3/output_3/2_a_main.PNG?raw=true" width=100% alt="stitch">

### Affine Structure from Motion

- Aims to reconstruct the 3D structure of a scene from a sequence of 2D images. 
- The goal is to recover the 3D positions of the points in the scene, as well as the camera poses and intrinsic parameters.

<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_3/output_3/3_b(ele90-azi180).PNG?raw=true" height =50% width=50% alt="sfm">

Camera position x | Camera position y | Camera position z
:-------------------------:|:-------------------------:|:-------------------------:
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_3/output_3/3_x.PNG?raw=true" width=100% alt="x"> | <img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_3/output_3/3_y.PNG?raw=true" width=100% alt="y"> | <img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_3/output_3/3_z.PNG?raw=true" width=100% alt="z"> 

[CLICK HERE](https://github.com/KACHAPPILLY2021/Computer_Vision_projects/tree/main/proj_3) - To view detailed project
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Project4 -->
## Project 4

### SLIC | Graphcut Segmentation

The outputs for this project is as follows:

### SLIC Superpixels
* Number of superpixels - 1024
* Weight Initialization - 20
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_4/output_4/1_main(k1024_m20).PNG?raw=true" height =35% width=35% alt="slic">

### Graphcut Segmentation 
Input Image  | Mask Image
:-------------------------:|:-------------------------:
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_4/output_4/2_a_input.PNG?raw=true" width=100% alt="cat"> | <img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_4/output_4/2_b_mask.PNG?raw=true" width=100% alt="mask">

* Likelihood map : $P(pixel/foreground)$
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_4/output_4/2_main_P(foreground).PNG?raw=true" height =25% width=25% alt="gmm">

[CLICK HERE](https://github.com/KACHAPPILLY2021/Computer_Vision_projects/tree/main/proj_4#readme) - To view detailed project
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Project5 -->
## Project 5

### Backpropagation | Image Classification | Semantic Segmentation
The outputs for this project is as follows:

### Basic Backpropagation in Neural Network


<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_5/output_5/1_main_acc.PNG?raw=true" height =30% width=30% alt="acc">

### Image Classification using CNN

*  (CIFAR-10 dataset)
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_5/output_5/2_loss.PNG?raw=true" height =35% width=35% alt="loss">

<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_5/output_5/2_conf.PNG?raw=true" height =35% width=35% alt="confusion">

### Semantic Segmentation using FCN 32

* (VGG 16 dataset)

Original | Ground Truth | FCN-32 output
:-------------------------:|:-------------------------:|:-------------------------:
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_5/output_5/3_input.PNG" width=100% alt="x"> | <img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_5/output_5/3_GT.PNG?raw=true" width=100% alt="y"> | <img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_5/output_5/3_fcn32.PNG?raw=true" width=100% alt="z"> 

[CLICK HERE](https://github.com/KACHAPPILLY2021/Computer_Vision_projects/tree/main/proj_5) - To view detailed project
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Prerequisites -->
## Prerequisites
* Free Google [Colab](https://colab.research.google.com/) version should be sufficient



<!-- CONTACT -->
## Contact

Jeffin Johny K - [![MAIL](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jeffinjk@umd.edu)
	
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/KACHAPPILLY2021)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](http://www.linkedin.com/in/jeffin-johny-kachappilly-0a8597136)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See [MIT](https://choosealicense.com/licenses/mit/) for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com
