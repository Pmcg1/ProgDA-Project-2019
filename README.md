# Programming for Data Analysis 2019 Project
## G00190832 Peter McGowan

## Introduction

This project has been carried out as an assignment of the Programming for Data Analysis module of the Higher Diploma In Data Analytics at GMIT. The project description can be found [here](https://github.com/brianmcgmit/ProgDA/blob/master/ProgDA_Project.pdf).

The repository contains a Jupyter Notebook that explores the project tasks in detail. The repository also includes:
* Readme file
* License file
* Gitignore folder
* Docs (Documents) folder
* Images folder

## Problem Statement

The aim of this project is to simulate a real-world phenomenon using Python.

The specific tasks are as follows:

1. Choose a real-world phenomenon that can be measured and for which you could collect at least one-hundred data points across at least four different variables;
2. Investigate the types of variables involved, their likely distributions, and their relationships with each other;
3. Synthesise/ simulate a data set as closely matching their properties as possible;
4. Detail your research and implement the simulation in a Jupyter notebook - the data set itself can simply be displayed in an output cell within the notebook.

## Approach

The data set that I have chosen to simulate is the [Adult Education Survey 2017](https://www.cso.ie/en/releasesandpublications/er/aes/adulteducationsurvey2017/) produced by the Central Statistics Office (CSO). In particular, I have chosen to simulate the 334 persons who participated in formal education. I have simulated these persons across four variables:
* Age
* Field of Education Participation
* Level of Education Participation
* Gender

These are described in more detail within the Jupyter notebook. Reports and data referred to are included for convenience at:
* [AES 2017 Main Report](data/20190124090303_Adult_Education_Survey_2017_full.pdf)
* [AES 2017 Quality Report](data/AES_17_Quality_report.pdf)
* [AES 2017 Table 2a: Persons aged 25-64 who participated in formal education, classified by the level of education participation](data/AES2017TBL2a.xlsx)
* [AES 2017 Table 2b: Persons aged 25-64 who participated in formal education, classified by the field of education participation](data/AES2017TBL2b.xlsx)
* [Census 2016 Table E3002: Population 2011 to 2016 (Number) by At Each Year of Age, Aggregate Town](data/E3002.csv)

## License

This project is licensed under the GNU General Public License v3.0 - see [LICENSE.md](LICENSE) for details.

## Jupyter Notebook

### Downloading the Repository

The repository is stored at [https://github.com/Pmcg1/ProgDA-Project-2019](https://github.com/Pmcg1/ProgDA-Project-2019).

To download it, do the following:

1. Click on the "Clone or Download" button
2. Select "Download ZIP". This will open a prompt allowing you to save the file to your computer.
3. Navigate to the download location and extract the compressed (.zip) folder to a suitable location.

### Software Required

The notebook has been written using Jupyter Lab v1.0.2. and Python v3.7.3 and should be run on a computer with these versions or higher if possible. I recommend that you download the current Python 3.x Anaconda Distribution (which contains both Python and Jupyter Lab) from the [downloads section](https://www.anaconda.com/distribution/#download-section) of the Anaconda Website.

When it has downloaded, follow the installation steps with the default options to install Anaconda on your computer.

You can check which (if any) versions of these that you have installed by typing the following at the command prompt:
* python --version
* jupyter --version

This project also requires a number of external Python libraries ([listed below](#Libraries-Used)). These come with the Anaconda Distribution and should not need to be installed separately, however links to the website for each are included.

### Libraries Used

- [Numpy](https://www.numpy.org/) - The numpy.random library is extensively used throughout this notebook.
- [Pandas](https://pandas.pydata.org/) - Pandas is used to manipulate and view data in table format predominantly. It is heavily used throughout.
- [Statsmodels](https://www.statsmodels.org/stable/index.html) - This is a library designed for statistical modelling and testing - it is used to calculate weighted statistics. 
- [Matplotlib.pyplot](https://matplotlib.org/tutorials/introductory/pyplot.html) - Used for manipulation of elements of certain plots in the notebook.
- [Seaborn](https://seaborn.pydata.org/) - Used for creation and manipulation of plots in the notebook.

Please note that the programmes will not run successfully if their required libraries are not installed.

### How to Run

Once the correct software has been installed, running either of the included programmes can be carried out as follows:

1. Open a command prompt (cmd) or equivalent on your PC. The alternative "cmder" programme ([available here](https://cmder.net/)) is recommended.
2. Navigate to the drive that the folder is on.
3. Navigate to the correct folder.
4. Run jupyter lab by typing the following at the command prompt (do not close the command prompt window throughout):
> jupyter lab

5. A window or tab should open in your default web browser (Mozilla Firefox and Google Chrome are recommended). If this does not happen, read the command prompt output. It should provide a URL which you can copy and paste into your web browser to access Jupyter Lab.
6. Using the menu on the left side of the page, double click the jupyter notebook file:
> ProgDA_Project_2019.ipynb

7. The notebook should open in a new tab. You can run each cell with the keyboard shortcut SHIFT+ENTER, alternatively use the "play" button on the menu bar. Please note that certain cells must be run before others e.g. the cells importing the various Python libraries. You may find it convenient to use the "Run all Cells" option in the "Run" dropdown menu.
