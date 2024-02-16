<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>


<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<br />
<div align="center">
  <a href="https://github.com/skyswpark/Week_4_Assignment">
  </a>

<h3 align="center">classifying_the_echoes_in_leads_and_sea_ice</h3>

  <p align="center">
    project_description
    <br />
    <a href="https://github.com/skyswpark/Week_4_Assignment"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/skyswpark/Week_4_Assignment">View Demo</a>
    ·
    <a href="https://github.com/skyswpark/Week_4_Assignment/issues">Report Bug</a>
    ·
    <a href="https://github.com/skyswpark/Week_4_Assignment/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
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
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This project aims to classify the echoes in leads and sea ice and produce an average echo shape as well as standard deviation for these two classes. For image classification K-means implementation and GMM implementation are used. Then these unsupervised methods are used for altimetry classification tasks, focusing specifically on distinguishing between sea ice and leads in Sentinel-3 altimetry dataset.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started


### Prerequisites

* This project uses Google Colab to run the scripts. When using Google Colab, you will need a Google account for access to Colab and your Google drive.
* Sentinel-2 optical data, Sentinel-3 OLCI, and altimetry data are used in this project. You will need an account (username and password) to download the data from the Copernicus dataspace.


<!-- USAGE EXAMPLES -->
## Functions

In SWP_Chapter1_Unsupervised_Learning_Methods_Michel.ipynb you will find:

* **peakiness** : Calculates the peakiness of waveforms, which is a measure that compares the maximum amplitude of a waveform to its average amplitude within a specific window around the peak.

* **unpack_gpod** : Handles the unpacking and interpolation of variables from a Generic Product Output Data (GPOD) format.

* **calculate_SSD** : Calculates the Sum of Squared Differences (SSD) for a set of waveforms, which is a measure of the variance or spread of each waveform around its mean.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/skyswpark/Week_4_Assignment/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Skylar Park - sun.park.20@ucl.ac.uk

Project Link: [https://github.com/skyswpark/Week_4_Assignment](https://github.com/skyswpark/Week_4_Assignment)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* University College London (UCL) Module GEOL0069: Artificial Intelligence for Earth Observation


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/skyswpark/Week_4_Assignment.svg?style=for-the-badge
[contributors-url]: https://github.com/skyswpark/Week_4_Assignment/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/skyswpark/Week_4_Assignment.svg?style=for-the-badge
[forks-url]: https://github.com/skyswpark/Week_4_Assignment/network/members
[stars-shield]: https://img.shields.io/github/stars/skyswpark/Week_4_Assignment.svg?style=for-the-badge
[stars-url]: https://github.com/skyswpark/Week_4_Assignment/stargazers
[issues-shield]: https://img.shields.io/github/issues/skyswpark/Week_4_Assignment.svg?style=for-the-badge
[issues-url]: https://github.com/skyswpark/Week_4_Assignment/issues
[license-shield]: https://img.shields.io/github/license/skyswpark/Week_4_Assignment.svg?style=for-the-badge
[license-url]: https://github.com/skyswpark/Week_4_Assignment/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
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
