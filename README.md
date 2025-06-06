# GPA Prediction with Deep Learning (TensorFlow)

This project uses a neural network implemented in TensorFlow to predict students' GPA based on demographic, academic, and personal factors.

##  Description

The goal is to build a regression model that predicts GPA (0 to 4) using various student features.

##  Dataset Features

- Age, Gender, Ethnicity
- Parental education, Study time, Absences
- Participation in tutoring, extracurriculars, sports, music, volunteering
- GPA (target value)

##  Model Architecture

- Input layer: One neuron per feature
- 1 or more hidden layers
- Output layer: 1 neuron (GPA as float)
- Loss: Mean Squared Error (MSE)
- Optimizer: Adam

##  Evaluation

- Cost function trend plotted over epochs
- R² score for test set
- Visualizations of predictions vs. true values

##  Requirements

```bash
pip install tensorflow pandas numpy scikit-learn matplotlib seaborn
