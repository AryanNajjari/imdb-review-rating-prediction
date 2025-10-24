# imdb-review-rating-prediction
🎬 IMDB Review Rating Prediction

This project uses Qwen, a large language model, to analyze movie reviews from the IMDB dataset and predict their corresponding numeric ratings (from 1 to 10). The model is fine-tuned on review–rating pairs and evaluated on unseen test data.

📘 Overview

This repository demonstrates a workflow for:

Cleaning and preparing the IMDB dataset

Training a Qwen model on textual movie reviews and their correlated ratings

Evaluating model accuracy and prediction quality on test reviews

Visualizing and analyzing model performance

🧠 Model

The model is based on Qwen — a transformer-based large language model.
It was fine-tuned using IMDB reviews where each review text corresponds to a numeric rating (1–10).

Key steps:

Preprocessing and tokenization

Fine-tuning on prompt–completion pairs

Evaluation on held-out test reviews

Generating predicted ratings

📈 Results

Over 60% of the test data points were predicted with exact accuracy or within ±1 of the actual rating, approximately 12% showed a ±2-point deviation, and about 28% differed by more than 2 points from the actual ratings.
