# Description

Built a Machine Learning model to detect emotions (sadness, joy, love, anger, fear, surprise) from text messages using Natural Language Processing techniques.

# Dataset

- text.csv
- 416,809 text messages
- Labels: sadness, joy, love, anger, fear, surprise

# Tools & Libraries Used

- Python
- Google Colab
- Pandas
- Scikit-learn
- Regex (re)

# Algorithm Used

- Logistic Regression

# Steps Involved

1. Data Collection
2. Text Cleaning (lowercasing, removing special characters)
3. Label Mapping (numeric to emotion names)
4. TF-IDF Vectorization
5. Train-Test Split (Stratified)
6. Model Training
7. Model Evaluation

# Result

- Accuracy: 90%
- Strong performance across all emotion classes, with sadness (0.94) and joy (0.91) predicted most precisely
- Surprise was the most challenging class due to fewer samples
