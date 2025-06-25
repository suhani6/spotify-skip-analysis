# 🎧 Spotify Skip Rate Analysis

This project analyzes user behavior on Spotify to predict whether a track will be skipped, using listening logs and audio features.

## 🔍 Problem Statement
Can we predict if a user will skip a song based on session context, track metadata, and user behavior?

## 🗂️ Dataset
- **Source**: [Kaggle - Spotify Skip Prediction Challenge](https://www.kaggle.com/datasets/thec03u5/spotify-1m-streams)
- `log_mini.csv`: User session logs
- `tf_mini.csv`: Track features

## 🔨 Techniques Used
- Exploratory Data Analysis
- Feature Engineering
- LightGBM Modeling
- Feature Importance Visualization

## 📊 Results
- **Accuracy**: 99%
- **ROC AUC**: 0.995
- Key Drivers of Skipping: Listening context, reason for playback start/end

## 📄 Report
See the full project report [here](Spotify_Skip_Analysis_Report.pdf).

## 🧠 Model
- Classifier: `LGBMClassifier`
- Feature Importance: `hist_user_behavior_reason_end`, `context_type`, `us_popularity_estimate`, etc.

## 🚀 How to Run
```bash
pip install -r requirements.txt
