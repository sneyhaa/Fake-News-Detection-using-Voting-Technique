# Fake News Detection using Voting Ensemble

This project investigates the effectiveness of a Voting Ensemble approach for detecting fake news articles. It explores a context-based linguistic approach for text pre-processing and compares the performance of individual machine learning algorithms with the ensemble classifier.

## Methodology

- Data Preprocessing: Text data from news articles undergoes pre-processing steps like stemming/lemmatization, stop word removal, and potentially other context-based techniques (e.g., part-of-speech tagging, named entity recognition).
- Feature Engineering: Extracted features from the pre-processed text are used for model training.
- Machine Learning Models: Individual models including Logistic Regression (LR), Naive Bayes (NB), Decision Tree (DT), XGBoost (XGB), and Stochastic Gradient Descent (SGD) are trained on the prepared data.
- Voting Ensemble: The predictions from all individual models are combined using a voting technique (e.g., majority vote) to create the ensemble classifier.
  
## Evaluation

The performance of all models is evaluated on three publicly available datasets of varying sizes (Fake News Dataset, Fake or Real News, Fake News Classification) from Kaggle. The evaluation utilizes metrics like Accuracy, Precision, Recall, and F1-score.

## Results

The Voting Ensemble classifier demonstrates competitive performance across all datasets, achieving the highest accuracy in the Fake or Real News dataset and performing close to the best model (LR) in the Fake News Classification dataset. The results suggest that the ensemble approach can be particularly effective for larger datasets.
