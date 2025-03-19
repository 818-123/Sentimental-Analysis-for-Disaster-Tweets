# Disaster Tweet Classification

## Overview
This project classifies disaster-related tweets using Natural Language Processing (NLP) techniques. It preprocesses text data and applies machine learning models to identify tweets related to real-world disasters.

## Features
- Text preprocessing: tokenization, stopword removal, stemming, and lemmatization.
- Feature extraction using TF-IDF.
- Classification using Naïve Bayes, Logistic Regression, and K-Nearest Neighbors (KNN).
- Best-performing model: Multinomial Naïve Bayes (80.7% accuracy).

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/disaster-tweet-classifier.git
   cd disaster-tweet-classifier
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the preprocessing script:
   ```bash
   python preprocess.py
   ```
2. Train and evaluate models:
   ```bash
   python train.py
   ```
3. Classify new tweets:
   ```bash
   python classify.py "Sample tweet text"
   ```

## Dataset
- The dataset consists of labeled tweets indicating whether they are disaster-related or not.

## Results
- Multinomial Naïve Bayes performed best with 80.7% accuracy.
- Logistic Regression and KNN were also evaluated.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.
