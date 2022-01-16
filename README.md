# loan_qualifier_app
[![LinkedIn][linkedin-shield]][linkedin-url]
<!-- [![License][license-shield]][license-url] -->

<!-- PROJECT LOGO -->
<br />
<p align="center">
    <img src="https://github.com/evianap/loan_qualifier_app/blob/main/readme_images/app_screenshot.png" alt="Logo" width="700" height="300">
  </a>

  <h3 align="center">loan_qualifier_app</h3>

  <p align="center">
    Automating Loan Eligibility Evaluation
    <br />
    <a href="https://github.com/evianap/loan_qualifier_app"><strong>Go to documents »</strong></a>
    <br />
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

This project is designed to ask a few qualifying questions to a prospective client to determine eligibility for a loan based on a set of parameters and today's rates pulled from a CSV. Then the user will be asked if (s)he wants to save the loans that (s)he's eligible for in a new csv file:

<img src="https://github.com/evianap/loan_qualifier_app/blob/main/readme_images/qualifying_loans_csv_screenshot.png" alt="loan_list_screenshot" width="450" height="650">

Code was also improved to incorporate an error message and closing program whenever an invalid number was provided for any of the variables that are requested from the user. Please note that if an string is provided, program will still crash. All collaborations for improvement are welcome.

<img src="https://github.com/evianap/loan_qualifier_app/blob/main/readme_images/error_screenshot.png" alt="screenshot_error_" width="450" height="250">


### Built With

<!-- This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples. -->

* [Python](https://www.python.org/)
* [Visual Studio Code](https://code.visualstudio.com/)

### Prerequisites

<!-- This is an example of how to list things you need to use the software and how to install them. -->
A variety of libraries were used and are needed for this program. They can be added using the below commands in terminal:

``` 
import csv
import sys
import fire
import questionary
from pathlib import Path 
```
[For more information on libraries click on this link]( https://docs.python.org/3/library/csv.html?highlight=csv#module-csv ) 



<!-- CONTACT -->
## Contact

Enrique Viana - [@evianap][linkedin-url] - j.enrique.viana@gmail.com

Project Link: [https://github.com/evianap/loan_qualifier_app](https://github.com/evianap/microcredit_loans_valuation)

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Kevin Lee](https://github.com/kevinclee26/)
* [Hitarth Smart](https://github.com/smarthitarth)
* [Sajal Sharma](https://github.com/sajal-sharma)
* [FastCapital360](https://www.fastcapital360.com/wp-content/uploads/2021/07/Graphic_01-9.jpg)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

<!-- [license-shield]: 
[license-url]:  -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/enriqueviana/
