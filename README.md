# jmpytools
A collection of tools for the life-cycle of complex models.

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Best-README-Template</h3>

  <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
  </p>
</p>


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
<!--
*** Thanks for checking out this README Template. If you have a suggestion that would
*** make this better, please fork the repo and create a pull request or simply open
*** an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->




<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Introduction](#introduction)
* [Model Development](#model-development)
* [Data Management](#data-management)
* [Model Execution](#model-execution)
* [Results Analysis](#results-analysis)
* [Model Goverance](#model-goverance)
* [Getting Started](#getting-started)
* [Prerequisites](#prerequisites)
* [Installation](#installation)

<!-- INTRODUCTION -->
## Introduction
A highly flexible data model allows that provides the following:

<!-- MODEL DEVELOPMENT -->
### Model Development
Calculation management is the process of managing what a model does—as in, what mathematical calculations are being performed, in what order and what level of detail is associated with those calculations. The management of these calculations is often a large focus of model governance practices, and this is to ensure calculations are doing what they are supposed to and are being used appropriately. 

<!-- DATA MANAGEMENT-->
### Data Management
Data management is the process of managing the data that is used to pass through the model calculations. It includes inputs to the model, assumptions used by the model, tables and other fixed external data sources, as well as the model results.

In many types of models, managing data also can be handled through version-control systems to track changes and versions of various assumptions. However, an additional layer of complexity comes in when there are multiple sets of assumptions that feed into the same inputs within a model.

#### Input Management
Manage inputs to projections, navigate between files and tables to enable streamlined comparisons between data sets. Combined with assumption sets, you can manage large sets of data with the ease and flexibility you've been wanting.

#### Dynamic Table Management
Define your table structures during model development and load data using a variety of approaches including direct file imports and easy-to-use table editors.

#### Assumption Set Management
Create groupings of assumptions that stack on one another to more easily control values at run time, while providing the flexibility necessary for complex scenarios.  Using a drag and drop editor, it's easier than ever to manage your assumption sets!

#### Field Level Validation
Real-time input validation which gives you instant feedback on potential issues to more easily avoid run-time errors.

<!-- MODEL EXECUTION -->
## Model Execution
Generally, most people want models that:

*  Produce accurate results.
* Use precise methods for all features.
* Run quickly.

### Distributive Processing
Distributive processing provides mechanisms for spreading workloads across multiple sets of hardware for parallel processing of calculations. This comes in several forms of increasing complexity. 

* Multi-threading takes several executable processes and splits the workload across the multiple cores, or threads, on a single machine.
* Grid computing takes this to the next level by splitting workloads across multiple machines connected via a closed network. 

### Cloud Computing
Cloud providers have a vast pool of resources available for computation, generally hosted on a virtual machine or web based server.

### Run Logging
Run logs help diagnose and resolve issues with inputs, formulas, or other aspects of the model. The model logs the steps that the calculation engine performs so you can easily identify problems, from incorrect results to performance bottlenecks.

<!-- RESULTS AND ANALYSIS -->
## Results and Analysis
Understanding what comes out of your models is important—really important. In fact, it’s most likely the reason why the model exists in the first place. However, getting to the truly useful information can sometimes be difficult. 

The reporting module is a fully-featured, robust solution, built on top of the most modern technologies. Allow users to build out custom reports, allowing for pivoting, drill-downs, and other powerful reporting capabilities.

### Dynamic Report Creation
Use built in dashboards and reports as a starting point, with the ability to save new custom reports or dashboards at any time to quickly access that data later.

### Powerful Visualizations
A library of available visualizations for analyzing the output of a financial projection.

### Simple Report Editing
Edit existing reports and dashboards as model objectives adapt using our highly flexible, embedded, visual report editor.

### TRANSPARENT DATA ACCESS
Work with high-level data to build visualizations of aggregated company or product results, or drill down into individual model points details. 

### FLEXIBLE DATA EXPORT
Prefer to look at the data in another tool. Result data can be easily exported into various formats.

### INSIGHTFUL DASHBOARDS
Customize your reports to answer the questions of your business. Create customized analytics for different processes.

<!-- MODEL GOVERNANCE -->
## Model Governance
Change management tools to enable the most robust model governance framework.

### Easily View Differences
Compare models with a few clicks. Easily see what variables, tables, and assumptions have changed in an easy to scan, side-by-side comparison view.

### Quickly Merge Changes
After viewing changes, merge them with the click of a button. Keep separate model versions for model features, and merge the changes when they are ready.


<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

There are many great README templates available on GitHub, however, I didn't find one that really suit my needs so I created this enhanced one. I want to create a README template so amazing that it'll be the last one you ever need.

Here's why:
* Your time should be focused on creating something amazing. A project that solves a problem and helps others
* You shouldn't be doing the same tasks over and over like creating a README from scratch
* You should element DRY principles to the rest of your life :smile:

Of course, no one template will serve all projects since your needs may be different. So I'll be adding more in the near future. You may also suggest changes by forking this repo and creating a pull request or opening an issue.

A list of commonly used resources that I find helpful are listed in the acknowledgements.

### Built With
This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* [Bootstrap](https://getbootstrap.com)
* [JQuery](https://jquery.com)
* [Laravel](https://laravel.com)



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
```sh
npm install npm@latest -g
```

### Installation

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
```sh
git clone https://github.com/your_username_/Project-Name.git
```
3. Install NPM packages
```sh
npm install
```
4. Enter your API in `config.js`
```JS
const API_KEY = 'ENTER YOUR API';
```



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [Animate.css](https://daneden.github.io/animate.css)
* [Loaders.css](https://connoratherton.com/loaders)
* [Slick Carousel](https://kenwheeler.github.io/slick)
* [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
* [Sticky Kit](http://leafo.net/sticky-kit)
* [JVectorMap](http://jvectormap.com)
* [Font Awesome](https://fontawesome.com)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=flat-square
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=flat-square
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=flat-square
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=flat-square
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
