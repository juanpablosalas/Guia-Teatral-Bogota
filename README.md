# Guia Teatral Bogotá

<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
<!-- [![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
--?



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/juanpablosalas/Guia-Teatral-Bogota">
    <img src="images/logo.png" alt="Logo" width="200">
  </a>

<h3 align="center">Bogotá Theater Guide</h3>

 <!-- <p align="center">
    project_description
    <br />
    <a href="https://github.com/github_username/repo_name"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/github_username/repo_name">View Demo</a>
    ·
    <a href="https://github.com/github_username/repo_name/issues">Report Bug</a>
    ·
    <a href="https://github.com/github_username/repo_name/issues">Request Feature</a>
  </p> -->
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
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com) -->

Bogotá is home to an enormous variety of theater groups and theater houses. This, combined with the constant visits from international companies pose the challenge on theatregoers of keeping track of the city's vast cultural offer. 
This project obtains information about plays and other performances in Bogotá and classifies them in order to be shared with the public via <a href ="https://calendar.google.com/calendar/u/1?cid=Y2xhc3Nyb29tMTE3MzkzNjM4MDM3NTEyMjg1ODA1QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20"> Google Calendar </a>.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Selenium][Selenium.js]][Selenium-url]
* [![Pandas][Pandas.js]][Pandas-url]
* [![NumPy][NumPy.js]][NumPy-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

In order to extract the information from the internet, you must install Selenium
  ```sh
  pip install selenium
  ```
  
 Make sure the <a href="https://selenium-python.readthedocs.io/installation.html#drivers"> driver </a> is also installed in your corresponding browser. The code is written for Safari, but any webdriver works. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

1. **Web scraping**: The first file that must be run is the `webscraping_guia.ipynb`. This notebook extracts information from the main ticketing and theater sites (Teatro Mayor, Atrapalo, Teatro Nacional, La Maldita Vanidad, Teatro La Candelaria, IDARTES, Teatro Colón,  Teatro Libre) and stores the information on `/data/guia_teatral(date).csv`.

2. **Cleaning**: The data cleaning process, found in `limpieza_guia.ipynb` involves mapping the genre of the show based on a dictionary of key words found in the title. This code also exports the file in a ready-to-import format for Google Calendar. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [X] Web scraping of main theater sites
- [X] Classification of events by genre
- [ ] Geoposition of events
- [ ] Implementation of text mining in order to predict genre using a play's description
- [ ] Prediction of plays by theater company and season


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

Your Name - [@juanpicoss](https://twitter.com/twitter_handle) - jp.salas@uniandes.edu.co

Project Link: [https://github.com/juanpablosalas/Guia-Teatral-Bogota](https://github.com/juanpablosalas/Guia-Teatral-Bogota)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
[Selenium.js]: https://img.shields.io/badge/selenium-43B02A.svg?&style=for-the-badge&logo=selenium&logoColor=white
[Selenium-url]: https://www.selenium.dev
[Pandas.js]: https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white
[Pandas-url]: https://pandas.pydata.org
[NumPy.js]: https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white
[NumPy-url]: https://numpy.org

