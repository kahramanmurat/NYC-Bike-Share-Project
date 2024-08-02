# NYC Bike Share Project

Welcome to the NYC Bike Share Project repository! This project aims to predict the trip duration of bike share trips in New York City using machine learning techniques. The project leverages various MLOps tools to create a robust, scalable, and monitored ML pipeline.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Pipeline](#pipeline)
- [Workflows](#workflows)
- [Setup](#setup)
- [Usage](#usage)
- [MLflow](#mlflow)
- [AWS-CICD-Deployment-with-Github-Actions](#aws-cicd-deployment-with-github-actions)
- [License](#license)

## Introduction

The goal of this project is to predict the duration of bike share trips in New York City. We use features such as trip distance, start station, and end station to train our machine learning models. The project is structured to ensure easy deployment, monitoring, and scalability using various MLOps tools.

## Project Structure

```plaintext
NYC-Bike-Share-Project/
│
├── .github/
│   └── workflows/
│
├── config/
│
├── mlruns/
│   └── 0/
│
├── research/
│
├── src/
│   └── mlProject/
│
├── static/
│
├── templates/
│
├── .gitattributes
├── .gitignore
├── Dockerfile
├── LICENSE
├── README.md
├── app.py
├── main.py
├── params.yaml
├── requirements.txt
├── schema.yaml
├── setup.py
├── template.py
└── test.py

## Pipeline

The pipeline of the project consists of the following stages:

Data Ingestion: Fetch raw data from the NYC Bike Share dataset.
Data Preprocessing: Clean and preprocess the data for model training.
Feature Engineering: Calculate trip distances and prepare features.
Model Training: Train the machine learning model using the prepared features.
Model Evaluation: Evaluate the trained model on validation data.
Model Deployment: Deploy the model for real-time predictions.

## Workflows

Update config.yaml
Update schema.yaml
Update params.yaml
Update the entity
Update the configuration manager in src/config
Update the components
Update the pipeline
Update main.py
Update app.py

## Setup

```sh
git clone https://dagshub.com/kahramanmurat/NYC-Bike-Share-Project.mlflow.git
cd NYC-Bike-Share-Project
```