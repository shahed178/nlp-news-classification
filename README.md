# News Topic Classification Using Natural Language Processing

This project automatically classifies BBC news articles into five categories:
Business, Entertainment, Politics, Sport, and Tech.

## Dataset

BBC News Dataset containing 2,225 news articles.
Source: https://www.kaggle.com/datasets/pariza/bbc-news-summary

## Preprocessing

- Lowercasing
- Removing punctuation and special characters
- Removing numbers
- Tokenization
- Stop-word removal
- Lemmatization
- Removing extra spaces

## Feature Extraction

TF-IDF (max_features = 5000)

## Models

- Multinomial Naive Bayes
- Logistic Regression

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score

## Results

| Model | Accuracy | Precision | Recall | F1-score |
|---|---|---|---|---|
| Multinomial Naive Bayes | 0.9865 | 0.9860 | 0.9871 | 0.9864 |
| Logistic Regression | 0.9798 | 0.9787 | 0.9795 | 0.9790 |

## How to Run

1. Open NLP_Final_Project.ipynb.
2. Upload bbc-text.csv.
3. Run all cells in order.
4. Review the model evaluation and error analysis results.
5. Use predict_news_topic() for the live demonstration.

## AI Assistance Acknowledgment

AI-assisted tools were used for guidance during code development and report organization.
The final implementation, execution, results, and explanations were reviewed by the project team.