# Sarcasm Detection using NLP

## Overview
This project focuses on sarcasm detection using natural language processing (NLP) techniques. The goal is to classify sentences as sarcastic or non-sarcastic using a fine-tuned BERT-based model. The dataset comprises annotated sentences, with labels determined through inter-annotator agreement.

## Features
- **Data Annotation:** Collected and labeled 120+ sentences from diverse sources.
- **Inter-Annotator Agreement:** Used Cohen's Kappa to measure agreement between annotators.
- **Fine-Tuned BERT Model:** Trained and optimized using Hugging Face Transformers.
- **Hyperparameter Tuning:** Experimented with learning rate, batch size, and epochs for optimal accuracy.
- **Error Analysis:** Evaluated model weaknesses, especially in handling idiomatic phrases.

## Dataset
The dataset consists of labeled sentences:
- **Sarcastic (S):** Sentences conveying irony, humor, or an opposite meaning.
- **Non-Sarcastic (NS):** Sentences meant to be taken literally.

Example:
- **Sarcastic:** "Oh great, another meeting to discuss the last meeting."
- **Non-Sarcastic:** "I had a wonderful time at the concert."

## Model Training
- Uses Hugging Face Transformers.
- Fine-tuned BERT for sequence classification.
- Training and validation data split (80-10-10 ratio).

## Future Improvements
- Enhance sarcasm detection for idiomatic expressions.
- Include context from preceding and following sentences.
- Experiment with other transformer models like RoBERTa and XLNet.
