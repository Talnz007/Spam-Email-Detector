# Spam Email Detector

A simple spam email detector built using Python's scikit-learn library. This project classifies emails as spam or non-spam using a Naive Bayes classifier and text vectorization techniques.

## Project Overview

This project demonstrates how to build a spam email classifier from scratch using machine learning techniques. The main steps involved are:

1. **Loading the Dataset**: Importing a dataset containing emails labeled as spam or non-spam.
2. **Preprocessing**: Transforming text data into numerical features using `CountVectorizer`.
3. **Model Training**: Training a Naive Bayes classifier (`MultinomialNB`) on the processed data.
4. **Model Evaluation**: Evaluating the performance of the model using classification metrics.
5. **Prediction**: Testing the model with sample email texts to classify them as spam or non-spam.
6. **Pipeline Integration**: Demonstrating the use of a scikit-learn pipeline to streamline the workflow.

## Dataset

The dataset used is `spam.csv`, which should be placed in the project directory. This dataset contains the following columns:

- `Category`: The label indicating if the email is 'spam' or 'ham' (non-spam).
- `Message`: The text content of the email.

## Installation

Clone this repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/spam-email-detector.git
cd spam-email-detector
pip install -r requirements.txt
```

## Requirements

This project requires the following Python packages:

- `pandas`
- `numpy`
- `scikit-learn`

You can install the required packages using pip:

```bash
pip install pandas numpy scikit-learn
```

## Contributing

Feel free to submit issues or pull requests if you have suggestions or improvements. Contributions are welcome!
