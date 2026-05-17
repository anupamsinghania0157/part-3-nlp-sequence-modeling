# NLP and Sequence Modeling Mini Project

## Objective
Build a text classification pipeline using traditional NLP and sequence modeling concepts.

## Dataset
customer_reviews_nlp.csv

## Tasks Performed
- Dataset exploration
- Text preprocessing
- TF-IDF vectorization
- Logistic Regression baseline model
- LSTM sequence model
- Evaluation and predictions

## Technologies Used
- Python
- Scikit-learn
- TensorFlow/Keras
- NLTK
- Pandas
- NumPy

## Why Text Must Be Converted into Vectors
Machine learning models cannot understand raw text directly. Text vectorization converts text into numerical format so that models can process patterns mathematically.

## Why RNNs Struggle with Long-Term Dependencies
RNNs forget earlier information when sequences become very long.

## How LSTMs Help
LSTMs use memory cells and gates to preserve important information for longer sequences.

## What Attention Solves
Attention helps the model focus on important words in a sequence instead of treating all words equally.

## Why Transformers Are Important
Transformers process text in parallel and power modern Generative AI systems such as ChatGPT and BERT.