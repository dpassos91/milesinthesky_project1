# Miles in the Sky Data Science Course - Final Project "Data Analytics 101"

This repository is part of the learning objectives of the [Data Science Course](https://milesinthesky.education/programs-by-miles/) provided by Miles in the Sky.

## Table of Contents

- [Introduction](#introuduction)
- [The data](#the-data)
- [Installation](#installation)
- [The code](#the-code)
- [Results](#results)


## Introduction

Credit score cards are a common risk control method in the financial industry. It uses personal information and data submitted by credit card applicants to predict the probability of future defaults and credit card borrowings. The bank is able to decide whether to issue a credit card to the applicant. Credit scores can objectively quantify the magnitude of risk.
Generally speaking, credit score cards are based on historical data. Once encountering large economic fluctuations, past models may lose their original predictive power.
The questions asked were:
1. What seem to be the main contributing variables/features to a high (or low) default risk? Are they significant?
2. What about the least contributing ones (if at all)? Do they make sense? Why?
3. Should we reject applicants according to all of these variables? If not, which ones we shouldn't consider and why? 
4. Are there any other variables besides the ones in the dataset that would help to better understand credit default risk?

It's important to not forget that credit card applications tend to have a meaningful impact on people’s lives, so there's a need to choose all the variables ***carefully***.

## The data

The dataset is avaiable [here](https://miles-become-a-data-scientist.s3.us-east-2.amazonaws.com/J1/M7/data/raw/credit_card_applications.csv).

## Installation

In order to view and run the code used in this project in your local machine, you can:

1. Download or clone this repository using git:
```
git clone github.com/dpassos91/milesinthesky_project1
cd milesinthesky_project1/
```
2. Install a python environment with jupyter notebooks (e.g., [anaconda distribution](https://www.anaconda.com/products/individual)).

3. Create an environment with the required packages by running on the anaconda shell:
```
conda env create -f environment.yml --name myenv
conda activate myenv
jupyter lab milesinthesky_project1.ipynb
```

## The code

The code that led to all the analysis/figures used in this project can be found in the notebook `milesinthesky_project1.ipynb`.

## Results

The main results can be found in the notebook `milesinthesky_project1.ipynb`.

---
**Disclaimer**_
 The author is not affiliated with any of the entities mentioned nor received any kind of compensation. The information contained in this work is provided on an "as is" basis with no guarantees of completeness, accuracy, usefulness or timeliness.
