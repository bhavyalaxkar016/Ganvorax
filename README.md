# Ganvorax – MiniMind AI

**A Small Language Model (SLM) built from scratch using Transformer architecture and PyTorch.**

## About the Project

MiniMind AI is an educational Deep Learning project designed to understand and implement the fundamental concepts of Transformer-based language models.

The model learns patterns from a small educational text dataset and generates text using next-character prediction.

## Technologies Used

- Python
- PyTorch
- NumPy
- Matplotlib
- Gradio
- Google Colab

## Model Architecture

The project implements the following components:

1. Character-level Tokenization
2. Token Embedding
3. Positional Embedding
4. Self-Attention
5. Multi-Head Attention
6. Feed Forward Network
7. Layer Normalization
8. Output Layer

## Model Configuration

| Parameter | Value |
|---|---|
| Embedding Dimension | 128 |
| Attention Heads | 4 |
| Transformer Layers | 4 |
| Batch Size | 32 |
| Block Size | 64 |
| Training Iterations | 1000 |
| Learning Rate | 0.0003 |
| Dropout | 0.1 |

## Features

- Transformer implementation from scratch
- Custom educational dataset
- Model training and validation
- Training loss visualization
- Text generation
- Model checkpoint saving
- Gradio chatbot interface

## Installation

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Running the Project

The original implementation is designed for Google Colab.

1. Open the notebook in Google Colab.
2. Select a runtime.
3. Run the notebook cells.
4. Train the Transformer model.
5. Test text generation.
6. Launch the Gradio interface.

## Project Structure

```text
Ganvorax/
├── README.md
├── project.py
├── requirements.txt
└── .gitignore
```

## Future Improvements

- Expand the training dataset.
- Improve text generation quality.
- Add model checkpoint loading.
- Improve chatbot responses.
- Deploy the model as a web application.

## Learning Objectives

- Understand Transformer architecture.
- Learn self-attention mechanisms.
- Implement a language model using PyTorch.
- Understand model training and evaluation.
- Explore Natural Language Processing.

## Author

Developed as a Deep Learning project.

**Project:** Mini
