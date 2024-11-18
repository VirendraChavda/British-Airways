# British Airways Sentiment Analysis and Prediction
### Author: Virendrasinh Chavda

This repository contains the analysis and predictive modeling for British Airways' customer reviews and booking data. The project leverages machine learning and natural language processing (NLP) to analyze customer sentiment and predict customer behavior. It aims to uncover insights into customer satisfaction and booking patterns, which can help improve services and enhance customer experience.

---

## Table of Contents
1. [Overview](#overview)
2. [Installation](#installation)
3. [Features](#features)
4. [Usage](#usage)
5. [Methodology](#methodology)
6. [Future Work](#future-work)
7. [Contributing](#contributing)
8. [License](#license)

---

## Overview

This project focuses on two primary aspects:
1. <strong>Customer Sentiment Analysis</strong>:
   - Analysis of customer reviews to classify sentiments (positive, negative, or neutral).
   - Identification of key drivers of customer satisfaction and dissatisfaction.

2. <strong>Booking Prediction</strong>:
   - Predict customer bookings using historical booking data.
   - Leverage predictive models to understand patterns in customer booking behavior.

Key techniques include data preprocessing, feature extraction, machine learning modeling, and visualization of insights.

---

## Installation

To set up and use this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/british-airways-analysis.git
   cd british-airways-analysis
   ```
2. Create a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebooks for analysis:
   ```bash
   jupyter notebook
   ```

## Features

### Sentiment Analysis
- Clean and preprocess customer reviews from the `BA_reviews.csv` dataset.
- Perform sentiment classification using NLP techniques and machine learning models.
- Visualize sentiment distribution and most common words in reviews.

### Booking Prediction
- Analyze and preprocess booking data from `customer_booking.csv`.
- Predict booking behavior using machine learning models.
- Evaluate model performance with metrics like accuracy, precision, and recall.

### Data Mining and Insights
- Identify key trends in customer satisfaction.
- Uncover factors influencing positive and negative reviews.
- Explore booking patterns and customer demographics.

---

## Usage

### Data Preprocessing
- Run the `data_mining.ipynb` notebook to clean and preprocess the datasets.
- Process text data for sentiment analysis and numerical data for booking predictions.

### Model Training
- Train machine learning models for sentiment analysis using `British Airways ML.ipynb`.
- Train booking prediction models using `British Airways ML-2.ipynb`.

### Visualization
- Generate plots and word clouds to visualize customer sentiment.
- Create histograms and scatter plots to analyze booking trends.

---

## Methodology

### Datasets
- <strong>`BA_reviews.csv`</strong>: Contains customer reviews and ratings for British Airways.
- <strong>`customer_booking.csv`</strong>: Includes historical booking data with customer demographics and booking details.

### Steps

#### Sentiment Analysis
1. Clean reviews (remove stopwords, punctuation, etc.).
2. Tokenize and vectorize text using TF-IDF.
3. Train classifiers like Logistic Regression or Random Forest to predict sentiment.

#### Booking Prediction
1. Analyze key features influencing bookings.
2. Train machine learning models like Decision Trees and Gradient Boosting.
3. Evaluate models using a test set.

#### Visualization
- Generate word clouds and sentiment distribution charts.
- Explore correlations between features in booking data.

---

## Future Work

### Model Improvements
- Experiment with deep learning models like LSTMs for sentiment analysis.
- Use advanced ensemble methods for booking predictions.

### Additional Features
- Incorporate external data like weather or flight delays for better prediction accuracy.

### Deployment
- Develop a web app to display sentiment analysis results and predictions.
- Integrate with customer feedback systems for real-time insights.

---

## Contributing

Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request. If you encounter any issues, open a GitHub issue for discussion.

---

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.
