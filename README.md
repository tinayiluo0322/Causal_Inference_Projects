# Causal Inference Projects

Welcome to the UDS Projects Repository! This repository contains a series of causal inference projects that leverage various statistical and machine learning techniques to analyze and infer causal relationships from diverse datasets. Below are detailed descriptions of each project included in this repository.

## A/B Testing the Udacity Website

### Project Description:
In this project, we analyze user behavior data from an A/B test conducted by Udacity to improve their onboarding process. The test aimed to determine the impact of a new feature that asks users about their available time commitment before starting a free trial. By comparing user behaviors between the control group and the treatment group, we estimate the effect of this new feature on user retention and satisfaction.

### Key Components:
- Data analysis of user behavior during the onboarding process.
- Application of A/B testing principles to estimate the effect of the new feature.
- Evaluation of statistical significance and practical implications of the test results.

### Dataset:
The dataset provided by Udacity includes user interactions with the onboarding process and their subsequent engagement with the platform.

### Resources:
- [Original writeup by Udacity](https://www.kaggle.com/tammyrotem/ab-tests-with-python/notebook)
- [Udacity's A/B Testing course](https://www.udacity.com/course/ab-testing--ud257)

## Decision Making from A/B Testing

### Project Description:
This project explores a nuanced approach to A/B testing by considering both statistical and practical significance. Using data from a marketing A/B test conducted by IBM Watson Analytics, we analyze the impact of a new promotion on sales and interpret the results through the lens of probability distributions and Monte Carlo simulations.

### Key Components:
- Analysis of A/B test data using Frequentist statistical methods.
- Interpretation of results as probability distributions for expected effects.
- Monte Carlo simulations to assess the likelihood of different outcomes.
- Comparison of Frequentist and Bayesian approaches to statistical analysis.

### Dataset:
The dataset consists of weekly sales data from a fast-food chain's marketing campaign, including variables such as market size, store location, promotion status, and sales figures.

### Resources:
- [IBM Watson Analytics marketing A/B test dataset](https://www.kaggle.com/datasets/chebotinaa/fast-food-marketing-campaign-ab-test)

## Marijuana Legalization and Violent Crime

### Project Description:
This project investigates the impact of marijuana legalization on violent crime rates in California. By analyzing drug arrest data and crime statistics before and after key legislative changes in 2010 and 2016, we test the hypothesis that drug legalization reduces violent crime by decreasing illegal drug market activities.

### Key Components:
- Analysis of crime rates in relation to changes in marijuana laws.
- Application of difference-in-differences methodology to estimate the causal effect of legalization on violent crime.
- Interpretation of findings in the context of drug policy debates.

### Dataset:
The dataset includes drug arrest records and violent crime statistics from California, spanning several years before and after the legalization events.

## Crime and Policing Expenditures Exploratory Questions

### Project Description:
In this exploratory project, we examine the relationship between crime rates and policing expenditures using county-level data from Massachusetts. The goal is to determine whether there is a substantial correlation between the amount spent on policing and the incidence of crime.

### Key Components:
- Exploratory data analysis of crime and policing expenditure data.
- Statistical tests to assess the strength and significance of the relationship.
- Visualizations to illustrate findings and support conclusions.

### Dataset:
The dataset includes county-level information on crime rates and policing expenditures in Massachusetts.

## Interpretable Modelling of Credit Risk

### Project Description:
This project focuses on developing interpretable models for predicting credit risk using data from a Brazilian credit company. By leveraging Generalized Additive Models (GAMs), we aim to create models that provide clear and understandable predictions, avoiding the pitfalls of black-box models in high-stakes decision-making contexts.

### Key Components:
- Implementation of Generalized Additive Models (GAMs) using the pyGAM library.
- Evaluation of model performance and interpretability.
- Discussion of the importance of interpretability in credit risk modeling.

### Dataset:
The dataset comes from the 14th Pacific-Asia Knowledge Discovery and Data Mining conference (PAKDD 2010) and includes credit card transaction data from 2006 to 2009.

### Resources:
- [Cynthia Rudin's commentary on interpretability](https://arxiv.org/abs/1811.10154)
- [pyGAM documentation](https://pygam.readthedocs.io/en/latest/notebooks/tour_of_pygam.html)

## Matching Exercise

### Project Description:
This project evaluates the impact of obtaining a college degree on earnings in the US using matching techniques. By employing the `dame-flame` Python package, we perform matching on categorical variables to estimate the causal effect of education on income.

### Key Components:
- Application of matching algorithms to estimate treatment effects.
- Comparison of matching techniques in Python and R.
- Analysis of the impact of a college degree on earnings.

### Dataset:
The dataset includes information on individuals' educational attainment and earnings in the US.

### Resources:
- [DAME-FLAME Python package](https://almost-matching-exactly.github.io/DAME-FLAME-Python-Package)
- [MatchIt R package](https://kosukeimai.github.io/MatchIt/index.html)

## Predicting Mortgage Delinquency Risk

### Project Description:
In this project, we build a predictive model to assess the likelihood of mortgage delinquency using real data from Freddie Mac. The goal is to help a mortgage servicing firm identify high-risk mortgages and make informed purchasing decisions.

### Key Components:
- Data preprocessing and feature engineering.
- Development of a predictive model using machine learning techniques.
- Evaluation of model performance and interpretation of results.

### Dataset:
The dataset includes information on US Standard single-family home mortgages purchased or insured by Freddie Mac, along with payment data from a three-year period.

### Resources:
- [Freddie Mac Single-Family Loan-Level Dataset](https://www.freddiemac.com/research/datasets/sf-loanlevel-dataset)

## Power Calculations and Experiment Planning

### Project Description:
This project involves planning a randomized experiment for an NGO named Bandhan in West Bengal, India. By conducting power calculations, we estimate the sample size needed to demonstrate the effectiveness of a program providing livestock, cash, and training to households in extreme poverty.

### Key Components:
- Power calculations to determine sample size requirements.
- Experiment design and planning.
- Retrospective comparison of power calculations with actual program outcomes.

### Dataset:
The dataset includes information from the actual program conducted by Bandhan in 2007, with follow-up data from subsequent years.

### Resources:
- [Bandhan NGO](https://www.bandhan.org/)

## Estimating Gender Discrimination in the Workplace

### Project Description:
This project estimates the effect of being a woman on workplace compensation using data from the 2018 US Current Population Survey (CPS). The analysis focuses on differential compensation and aims to quantify the extent of gender discrimination in the workplace.

### Key Components:
- Analysis of workplace compensation data.
- Estimation of the effect of gender on earnings.
- Discussion of findings in the context of gender discrimination.

### Dataset:
The dataset includes workplace compensation information from the 2018 US Current Population Survey (CPS).

## Resume Experiment Analysis

### Project Description:
This project analyzes data from a real-world experiment designed to measure the effect of race on the likelihood of getting a job in the US. By examining the response rates to resumes with Black- or White-sounding names, we estimate the impact of racial discrimination on job opportunities.

### Key Components:
- Analysis of resume response data.
- Estimation of the effect of race on job callback rates.
- Interpretation of findings in the context of racial discrimination.

### Dataset:
The dataset includes information from a randomized experiment conducted in 2001, where fictitious resumes were sent to employers in Boston and Chicago.

### Resources:
- [Original article on the experiment](https://www.aeaweb.org/articles?id=10.1257/0002828042002561)
