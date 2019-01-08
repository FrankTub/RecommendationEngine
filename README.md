# IBM Recommendation Engine

## Table of contents

- [Installation](#installation)
- [Instructions](#instructions)
- [Project motivation](#project-motivation)
- [File descriptions](#file-descriptions)
- [Results](#results)
- [Creator](#creator)
- [Thanks](#thanks)


## Installation

In order to be able to execute your own python statements it should be noted that scripts are only tested on **anaconda distribution 4.5.11** in combination with **python 3.6.6**. 

Two quick start options are available:
- [Download the latest release.](https://github.com/FrankTub/RecommendationEngine/zipball/master/)
- Clone the repo: `git clone https://github.com/FrankTub/RecommendationEngine.git`

### Instructions:
TBC

## Project motivation
For the second term of the nanodegree [become a data scientist](https://eu.udacity.com/course/data-scientist-nanodegree--nd025) of [Udacity](https://eu.udacity.com/) I got involved in this project.

## File descriptions

Within the download you'll find the following directories and files.
TBC
```text
RecommendationEngine/
├── README.md
├── ETL Pipeline Preparation.ipynb # Notebook to prepare cleaning function
├── ML Pipeline Preparation.ipynb # Notebook to test out machine learning algorithms
├── app/
    ├──	run.py # Flask file that runs app
    ├── templates/
    |       ├──	master.html  # main page of web app
    |       └── go.html  # classification result page of web app  
├── data/
    ├── categories.csv  # data to process
    ├──	messages.csv  # data to process
    ├── process_data.py
    └── DisasterResponse.db   # database to save clean data to
└── models/
    ├── train_classifier.py
    └──	classifier.pkl  # saved model, not stored in github repository due to size, run ML pipeline to create this model.
```

## Results
TBC

## Creator

**Frank Tubbing**

- <https://github.com/FrankTub>


## Thanks

<a href="https://eu.udacity.com/">
  <img src="https://eu.udacity.com/assets/iridium/images/core/header/udacity-wordmark.svg" alt="Udacity Logo" width="490" height="106">
</a>

Thanks to [Udacity](https://eu.udacity.com/) for setting up the projects where we can learn cool stuff!

<a href="https://www.ibm.com">
  <img src="https://www.7men.nl/wp-content/uploads/2015/12/IBM-banner.jpg" alt="IBM Logo" width="490" height="106">
</a>

Thanks to [IBM](https://www.ibm.com) for providing cool data with which we can create a cutting edge project!
