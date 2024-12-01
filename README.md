# Sentiment_Analysis_using_ML
Analyzes the statement and decides whether it is positive or negative.(Using user-defined datset)

Sentiment Analysis AI Project:
This project is a sentiment analysis tool that uses machine learning to classify text into positive (1) or negative (0) sentiment. It efficiently processes data, supports larger input datasets, and includes various enhanced features to provide accurate sentiment predictions.

Features:
Efficient Model: Optimized for speed and accuracy, capable of handling larger datasets.
Customizable Data Input: Supports diverse datasets in .csv format.

Preprocessing:
Tokenization
Stop-word removal
Lemmatization for normalized input
Lowercasing for consistency
Model Training: Uses advanced classification algorithms, with flexibility to use SVM, Logistic Regression, or Neural Networks.
Cross-Validation: Implements k-fold validation for better generalization.
Detailed Output: Includes confusion matrix, accuracy, precision, recall, and F1 score to evaluate model performance.

Getting Started
Prerequisites
Python 3.8+
Required libraries:
pandas
numpy
scikit-learn
nltk
matplotlib

Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/sentiment-analysis-ai.git  
cd sentiment-analysis-ai  

Install dependencies:
bash
Copy code
pip install -r requirements.txt  

Dataset
Prepare your dataset as a CSV file with two columns:
Text: The input text for analysis.
Sentiment: The target sentiment (1 for positive, 0 for negative).
You can also use the provided sendiment_dataset.csv in the data/ folder.

Example
Input text:
text
Copy code
"The movie was fantastic! I enjoyed every moment."  
Predicted sentiment:
Positive (1)  

Output Samples:

![image](https://github.com/user-attachments/assets/da7a0d1a-05a7-44c6-9735-182286a04404)

Email: rahulvijay308@gmail.com
GitHub: RAHUL-V308
