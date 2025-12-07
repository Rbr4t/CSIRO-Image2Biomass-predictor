Introduction-to-Data-Science-LTAT.02.002
---
# CSIRO - IMAGE2BIOMASS PREDICTION
Building a model that predicts biomass using the provided pasture images

Link to the competition: https://www.kaggle.com/competitions/csiro-biomass

Team

    Robert Koor - R4brt
    Anneli Oro - anneli-oro

## Goals & Motivation

- Build a model that can help farmers to better estimate the amount of feed available and track pasture health more accurately.
- Model is able to predict 5 biomass components (Dry green vegetation (excluding clover), Dry dead material, Dry clover biomass, Green dry matter (GDM), Total dry biomass) based on pasture images
- Get $R^2$ score of 0.5 or higher

## Contents of the repository

``GROUP_D6_report.pdf`` - Our project report. Business and data understanding and project plan<br/>

``final_model.ipnyb`` - our final model, that scored 0.35.

*Main branch contains final version of our model, other models can be found on separate branches*

## Results

1. Our model achieved **$R^2$ score of 0.35** in the Kaggle environment.

Not exactly meeting our expectations, but we did design, build and train a model that predicted biomass components based on imput images.

## How to reproduce our score

Although it is technically possible to run this notebook locally by adjusting the file paths and configuration variables, **we recommend running it in the Kaggle environment**.
The notebook is set up to use a GPU, and even with GPU acceleration the full training process takes about 30 minutes.

