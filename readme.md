# Recommending Systems Project
> Neural Network Recommender - Adam Hącia 2022

## Table of contents
- [Recommending Systems Project](#recommending-systems-project)
	- [Table of contents](#table-of-contents)
	- [Achieved results compared to Amazon and Netflix Recommenders](#achieved-results-compared-to-amazon-and-netflix-recommenders)
	- [Project Description](#project-description)
	- [Technologies](#technologies)
	- [Setup](#setup)
	- [Status](#status)
	- [Contact](#contact)

## Achieved results compared to Amazon and Netflix Recommenders
![Example screenshot](images/img.png)

## Project Description

Implementation of neural network recommender which includes:
- loading and preparing data
- extraction of user and item features
- neural network model
- tuning of the model
- comparison to Netflix and Amazon Recommenders

Project is based on real data taken from hotel reservations. At the end of the document there is comparison between Amazon and Netflix recommenders and NNRecommender at HR@10 measure. 

## Technologies
* Python 3.9.7
* Anaconda + Jupyter

## Setup
1. Install Anaconda with Python >= 3.8.
2. Prepare your conda environment
     + Run the following command:
    ``` conda create -n recommender python=3.8```
     + Activate the conda environment by running:
    ``` conda activate recommender ```
3. Install the required packages
     + Run the following commands:
    ``` conda install numpy ```
    ``` conda install pandas ```
    ``` conda install matplotlib ```
    ``` conda install seaborn ```
    ``` conda install sklearn ```
    ``` conda install hyperopt ```
    ``` conda install livelossplot ```
4. In Bash type:
   ```jupyter notebook```
   The notebook will be opened in your browser.
5. In Jupyter Notebook open these files and run all cells:
   ```project_1_data_preparation```
   ```project_1_recommender_and_evaluation```
6. Last cell in `project_2_recommender_and_evaluation.ipynb` should contain the results of the evaluation with HR@10 metric for 
   * NetflixRecommender
   * AmazonRecommender
   * NNRecommender

## Status
Project is: _completed_

## Contact
Created by [@HondaPL](https://github.com/HondaPL/)