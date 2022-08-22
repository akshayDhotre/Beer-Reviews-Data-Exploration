# Beer-Reviews-Data-Exploration
Data exploration on Beer reviews containing various ratings and text reviews to find out answers to below questions - 

1.	Rank top 3 Breweries which produce the strongest beers?
2.	Which year did beers enjoy the highest ratings? 
3.	Based on the user’s ratings which factors are important among taste, aroma, appearance, and palette?
4.	If you were to recommend 3 beers to your friends based on this data which ones will you recommend?
5.	Which Beer style seems to be the favorite based on reviews written by users? 
6.	How does written review compare to overall review score for the beer styles?
7.	How do find similar beer drinkers by using written reviews only? 

Contents
========

 * [Folder Structure](#folder_structure)
 * [Installation](#installation)
 * [Usage](#usage)


## Folder Structure
````
BEER-REVIEWS-DATA-EXPLORATION
                            |---data
                            |---models
                            |---notebooks
                            |---reports
                                |---figures
                            |---venv
````

- data
  - This folder is not present in repo but needs to be created and data should be downloaded from [here](https://drive.google.com/open?id=1e-kyoB97a5tnE7X4T4Es4FHi4g6Trefq)
  - There are steps in code where we create intermideate data files that also are stored in this folder
- models
  - Folder to store if any model is saved 
- notebooks
  - This is for saving jupyter notebooks used for experimentation
- reports
  - This is used to store any rpoerts generated
  - It has subfolder for storing any plots and figures generated
- venv
  - This folder is created by name of your virtual environment

- Additional file 'requirements.txt' is to create working environment for this project


## Installation
----
#### Clone the repo using git or download zip file from github
````
git clone https://github.com/akshayDhotre/Beer-Reviews-Data-Exploration.git
````

#### Create virtual environment in python
#### For Linux - Ubuntu / Linux Mint
```bash
$ python3 -m venv /path/to/new/virtual/environment
```
#### For windows 
```bash
$ python -m venv c:\path\to\myenv
```

#### Activate environment 
#### For Linux - Ubuntu / Linux Mint
```bash
$ source project-env/bin/activate
```
#### For windows 
```bash
$ project-env\Scripts\activate.bat
```

#### Install required packages from requirement.txt file
```bash
$ pip install -r requirements.txt
```

## Usage
- Once everything is setup, you can start cells in jupyter notebook one by one.
> **Warning**
> Some of text processing steps need some more time to get completed than other steps. This depends on hardware that is used

- The jupyter notebook included in 'notebooks' folder has pre executed cells with inline comments and observations

- Verbal answers are collected in 'Answers.pdf' file available in 'reports' folder
- Power point presentation is available in 'reports' folder