# Tweet Sentiment Analysis Using BERT

# Objective
The primary aim of this project is to build a real-time sentiment analysis tool that classifies tweets as Negative, Neutral, or Positive. This helps in understanding public opinion and sentiments in an efficient manner.

# Goal
The goal is to create an accurate and scalable sentiment analysis solution that can handle real-time user input and provide meaningful insights into tweet sentiments.

# Model Used
The project employs a fine-tuned BERT (bert-base-uncased) model, known for its robust performance in natural language processing tasks. This pre-trained transformer model is adapted for multi-class classification to predict the sentiment of a given tweet.

# Working Process

Data Preparation:

Tokenized input text using BERT tokenizer.

Generated input IDs and attention masks.

Applied padding and truncation for uniform sequence length.

Model Architecture:

Leveraged BERT’s embeddings as input.

Integrated a dense output layer with softmax activation for multi-class classification.

Trained with categorical crossentropy loss and an exponential decay learning rate.

Training & Evaluation:

Fine-tuned the model on a labeled dataset while monitoring validation metrics to avoid overfitting.

# Deployment
The final model was deployed using Gradio to create an interactive web interface. This platform allows users to input a tweet and receive instant sentiment predictions, making it accessible and user-friendly. The interface includes custom styling and markdown for clear instructions.

