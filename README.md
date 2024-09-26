# Notebooks

### Fine-tuning a LLaMA 3.1 8B Conversational Model & Dataset Preprocessing

## Overview

This project contains two Jupyter notebooks aimed at preparing datasets and fine-tuning a LLaMA 3.1 8B Conversational model for specialized tasks. The workflow includes:

1. **Dataset Preprocessing**: Preparing and cleaning datasets to ensure compatibility with model training.
2. **Fine-tuning LLaMA 3.1 8B**: Training a conversational model using the preprocessed dataset.

---

## Notebooks

### 1. PreProcess_Dataset.ipynb

This notebook is responsible for preparing the dataset before it's fed into the model. It performs tasks such as:

- **Data Cleaning**: Removing missing or inconsistent values.
- **Text Preprocessing**: Tokenization, lowercasing, removal of stop words, and special characters.
- **Splitting Data**: Dividing the dataset into training, validation, and testing subsets.
  
Key libraries used in this notebook include:
- `pandas`
- `numpy`
- `nltk`
  
By the end of this notebook, the dataset will be ready for use in the fine-tuning process.

### 2. Llama_3_1_8b_Conversational_finetuning.ipynb

This notebook covers fine-tuning the **LLaMA 3.1 8B conversational model** using the preprocessed dataset. It includes:

- **Model Setup**: Loading the LLaMA 3.1 8B model.
- **Dataset Loading**: Loading the preprocessed dataset for training.
- **Fine-tuning Process**: Adjusting the model to improve conversational capabilities using the dataset.
- **Evaluation**: Evaluating the model's performance using various metrics (e.g., perplexity, accuracy).
  
Key libraries used in this notebook include:
- `transformers`
- `datasets`
- `torch`

---

