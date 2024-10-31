# BERT Fine-Tuning for Toxic Comment Classification

This project fine-tunes the BERT model to classify comments based on toxicity, enhancing performance in identifying negative or offensive comments.

## Project Overview

This repository contains a Jupyter notebook that fine-tunes the BERT model for a toxic comment classification task. Leveraging the transformer architecture, BERT is adapted to distinguish between different types of comments, aiming to filter out toxic content.

## Requirements

    pip install torch transformers pandas scikit-learn

### Main Dependencies

- **Python 3.7+**
- **Transformers**: For working with BERT and other transformer models.
- **PyTorch**: Provides the deep learning backend for model training.
- **Pandas**: Used for data handling and manipulation.
- **Scikit-learn**: Supplies tools for model evaluation and metrics.

## Data Preparation

Ensure you have a dataset containing job descriptions and associated salary ranges. In the notebook:

- Job descriptions are cleaned and tokenized using the BERT tokenizer.
- Data is split for training and evaluation.

## Model Training and Evaluation

The notebook includes code to:

- Preprocess and tokenize job descriptions.
- Fine-tune BERT for salary prediction tasks.
- Evaluate the model using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
