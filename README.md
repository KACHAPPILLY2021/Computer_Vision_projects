<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">


  <h1 align="center">First Principles of Computer Vision</h1>


</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#demo">Demo</a></li>
      </ul>
    </li>
    <li>
      <a href="#documentation">Documentation</a>
      <ul>
        <li><a href="#report">Report</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributors">Contributors</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>



<!-- ABOUT THIS REPO -->
## About This Repository



This repository contains all the projects that I implemented for my graduate course : Computer Processing of Pictorial Information.
All major Computer Vision concepts implemented here were developed from scratch ```without``` utilizing ```OpenCV's built-in``` functions.

Below are the outputs for each project and their associated links to view them.

```DISCLAIMER``` : Please note that in the future, the input data may no longer be accessible as it was obtained from the university server.



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Project1 -->
## Hybrid Images | Pyramid Image | Edge Detection | Template Matching

The outputs for this project is as follows:

### Hybrid Images
* Einstein and Marlyn Monroe hybrid image
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_1/output_1/1_main.PNG?raw=true" width=75% alt="hybrid">

### Pyramid Image
Original Image | Reconstructed Image
:-------------------------:|:-------------------------:
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_1/texture.jpg?raw=true" width=40% alt="original"> | <img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_1/output_1/2_main.PNG?raw=true" width=30% alt="reconstructed">

### Edge Detection
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_1/output_1/3_main.PNG?raw=true" width=100% alt="hybrid">

### Template Matching
* Puzzle Piece to find
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_1/output_1/4_waldo.PNG?raw=true" width=10% alt="hybrid">

* Waldo identified in Map
<img src="https://github.com/KACHAPPILLY2021/Computer_Vision_projects/blob/main/proj_1/output_1/4_puzzle.PNG?raw=true" width=50% alt="hybrid">

Detailed decription for this project can be found [here](https://github.com/KACHAPPILLY2021/Computer_Vision_projects/tree/main/proj_1)
<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

These are the instructions to get started on the project.
To get a local copy up and running follow these simple steps.

### Prerequisites
* atleast C++17
* OS - Linux (tested)


### Installation

Installing the micromouse simulator and running the code.

1. Make directory
   ```sh
   mkdir ~/RWA2_simulator
   ```
2. Clone the repos
   ```sh
   cd ∼ /RWA2_simulator
   ```
   ```sh
   git clone https://github.com/mackorone/mms.git
   ```
   ```sh
   git clone https://github.com/micromouseonline/mazefiles.git
   ```
   ```sh
   git clone https://github.com/KACHAPPILLY2021/maze_solving_algorithm.git
   ```
3. Compile Simulator
   ```sh
   sudo apt-get install qt5-default
   ```
   ```sh
   cd mms/src
   ```
   ```sh
   qmake && make
   ```


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

How to start simulator and use this DFS code in it.
1. Start simulator
   ```sh
   cd ∼ /RWA2_simulator/mms/bin
   ```
   ```sh
   ./mms
   ```
2. Choose any maze type and Click on the + button as shown in figure.

3. **Directory**: Click Browse and navigate to 'maze_solving_algorithm'
4. Enter **Build command** as:
   ```sh
   g++ src/main.cpp src/mouse.cpp src/node.cpp src/api.cpp
   ```
5. Enter **Run Command** as :
  ```sh
  ./a.out
  ```
6. Then Press **Build**, followed by **RUN** under the **Controls** Section
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTORS -->
## Contributors

Here are the

<p align="right">(<a href="#readme-top">back to top</a>)</p>



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
