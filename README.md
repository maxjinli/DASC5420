# DASC 5420 Final Project: Bayesian Logistic Regression for Wine Quality Prediction

This project utilizes Bayesian logistic regression for feature selection to predict wine quality based on chemical properties of wines from a specific region in Italy. The goal is to enhance predictive modeling by leveraging Bayesian methods to account for parameter uncertainty and determine the relevance of various features in predicting wine quality.

## Project Overview

The traditional approach in feature selection often overlooks the uncertainty associated with model parameters. This project adopts Bayesian logistic regression to incorporate prior knowledge and probabilistic reasoning into the feature selection process, using the Metropolis-Hastings algorithm to approximate the posterior distributions of model parameters. This methodology allows for a more nuanced understanding of feature importance and model dynamics.

### Key Objectives:
- Implement Bayesian logistic regression for feature selection.
- Evaluate the performance of the model using chemical properties of wine.
- Compare traditional logistic regression with a Bayesian approach to highlight the benefits and challenges of incorporating Bayesian methods.

## Repository Structure

    /DASC5420
    │
    ├── data/                   
    │   └── red_wine_scaled.csv         # Proprocessed data    
    │
    ├── notebooks/              
    │   └── Model_Training.ipynb        # Project notebook 
    │
    ├── results/                
    │   ├── traceplots/ 
    │   │   ├── beta_trace.png          # Traceplots of beta
    │   │   └── betagamma_trace.png     # Traceplots of beta*gamma
    |   └── posterior_betagamma.png     # Posterior of beta*gamma
    │   └── performance_metrics.txt     # Model performances
    │
    └── README.md 
