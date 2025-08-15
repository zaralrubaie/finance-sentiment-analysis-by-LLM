Financial Sentiment Classification using DistilBERT
Project Overview:
This project is a financial sentiment analysis system built with a small language model (DistilBERT). The model classifies financial sentences into sentiment categories such as positive, neutral, or negative. It demonstrates a full end-to-end NLP workflow, including data preprocessing, model fine-tuning, evaluation, and deployment via a Gradio interactive interface.

Motivation
Financial sentiment analysis is critical in understanding market trends, investor sentiment, and news impact. Automating this process can help analysts and investors make faster and more informed decisions.

Dataset
The dataset consists of financial sentences and their corresponding sentiment labels.
Columns:
Sentence: The text of a financial statement or news headline.
Sentiment: Encoded label (positive, neutral, negative).

Project Features
Uses DistilBERT, a lightweight transformer model, for text classification.
Splits data into training, validation, and test sets.
Fine-tunes the pretrained model on the financial sentiment dataset.
Provides evaluation metrics (accuracy, loss) after training.
Includes a Gradio web interface for interactive testing of new financial sentences.Its a temperory link for one week only,can be updated later.
Fully portable Python script for easy deployment and experimentation.

Installation & Setup:
1. Clone the repository
git clone https: https://github.com/zaralrubaie/finance-sentiment-analysis-by-LLM/edit/main/README.md
cd financial-sentiment-llm
git add .
git commit -m "Initial commit - financial sentiment LLM project"
git push origin main

2. Install dependencies
pip install -r requirements.txt

Usage:
run : python sentiment_classifier.py

Example sentences for testing:
"The company reported a record profit this quarter."  # → positive
"Stock prices dropped sharply after the earnings report."  # → negative
"Investors are worried about rising inflation rates."  # → neutral

Skills Demonstrated:
NLP / Text Classification
Transformers / Hugging Face
Model Fine-tuning
Data Preprocessing (train-test-val split, tokenization)
Evaluation Metrics & Model Interpretation
Basic Deployment with Gradio
