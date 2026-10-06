# Grammar Scoring Engine

A machine learning project developed to predict the grammatical proficiency of spoken English from audio samples. The system processes 45–60 second speech recordings and predicts a continuous Grammar Score between 0 and 5 based on the provided MOS-based scoring rubric.

## Objective

The objective is to develop an automated Grammar Scoring Engine capable of estimating the grammatical quality of spoken English using audio data and machine learning techniques.

## Dataset

- **Training samples:** 769 audio recordings
- **Testing samples:** 216 audio recordings
- **Audio format:** WAV
- **Input:** Spoken English audio
- **Output:** Continuous grammar score from 0 to 5

## Methodology

The project covers the complete machine learning pipeline:

1. Audio data preprocessing
2. Audio feature extraction
3. Exploratory data analysis
4. Feature engineering and selection
5. Model development and training
6. Validation and performance evaluation
7. Prediction on unseen test samples
8. Submission generation

## Evaluation Metrics

Model performance is evaluated using:

- **Pearson Correlation** – measures the correlation between predicted and actual grammar scores.
- **RMSE (Root Mean Squared Error)** – measures the prediction error.

The training-data RMSE is also reported as required by the competition.

## Visualizations

The notebook includes relevant visualizations to analyze the dataset, feature distributions, model performance, and predicted versus actual grammar scores.

## Technologies

Python, NumPy, Pandas, Scikit-learn, Librosa, Matplotlib, Seaborn, and Jupyter Notebook.

## Competition Context

This project was developed as part of a machine learning competition focused on automated assessment of spoken English grammar. The goal is to build an effective and interpretable pipeline for predicting human-assigned grammar scores from speech.
