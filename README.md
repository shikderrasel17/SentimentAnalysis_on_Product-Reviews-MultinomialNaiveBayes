# SentimentAnalysis_on_Product Reviews-MultinomialNaiveBayes

## Overview
This project involves the development of a machine learning model using Multinomial Naive Bayes to classify product reviews into three sentiment categories: Positive, Neutral, and Negative. The model is trained on a dataset of product reviews and evaluated using several performance metrics.

## Repository Name
**Logistic SentimentAnalysis_on_Product Reviews-MultinomialNaiveBayes**

## Model Details
- **Model**: Multinomial Naive Bayes
- **Algorithm**: Naive Bayes classifier designed for use with features that are distributed according to a multinomial distribution.
- **Preprocessing**: CountVectorizer is used to convert the text data into a matrix of token counts.

## Intended Use
This project is intended for sentiment analysis of product reviews. It can be used to:
- Automate the categorization of reviews.
- Analyze customer feedback to gauge overall sentiment.
- Improve customer service by identifying trends in customer satisfaction.

## Data Source(s)
The dataset consists of product reviews labeled with their corresponding sentiment. The data is loaded from a CSV file named `product_reviews.csv`.

## Dataset Sample
| Review | Sentiment |
|--------|-----------|
| This product exceeded my expectations! It's high-quality and performs exceptionally well. | Positive |
| The product was decent. It worked fine, but it wasn't anything special. | Neutral |
| I had a terrible experience with this company. The customer service was rude and unhelpful. | Negative |
| It's an okay product. Nothing to write home about. | Neutral |
| Disappointed with the product. It didn't meet my expectations. | Negative |

## Training Data
The training data consists of product reviews, which are split into a training set (70%) and a testing set (30%) using `train_test_split`.

## Test Data
The test data is used to evaluate the model's performance after training. It includes a separate set of reviews not seen during the training phase.

## Parameters
- **Train-Test Split**: 70% training, 30% testing.
- **Vectorization**: CountVectorizer for converting text data into numerical features.
- **Model Hyperparameters**: Default settings for the Multinomial Naive Bayes classifier.

## Feature Importance
The model does not directly provide feature importance scores. However, the CountVectorizer generates token counts, which serve as the features for the model.

## Metrics
- **Accuracy**: Measures the proportion of correct predictions.
- **Precision**: Evaluates the accuracy of positive predictions.
- **Recall**: Measures the ability of the model to identify all relevant cases.
- **F1 Score**: A harmonic mean of precision and recall.

## Results
The model achieved high performance on the test data, with metrics indicating strong predictive capabilities:
- **Accuracy**: 99.14%
- **Precision**: 99.15%
- **Recall**: 99.14%
- **F1 Score**: 99.13%

## How to Run
1. Clone the repository.
2. Load the dataset `product_reviews.csv` into your environment.
3. Run the provided Python script to train the model and evaluate its performance.
4. Use the model to predict sentiments of new reviews.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
This project was developed as part of a machine learning course. Special thanks to the instructors and peers who provided valuable insights and feedback.

---

Feel free to explore the repository and use the code for your own projects. Contributions are welcome!
