# GPT-2 Implementation

## Overview
This repository contains a custom implementation of **GPT-2** from scratch using **PyTorch**. The model is a **decoder-only transformer** that can perform **text completion, autocompletion, and generation**. It follows the core architecture of OpenAI's GPT-2 but is implemented with a custom training pipeline.

## Features
- **Custom Transformer Architecture**: Includes multi-head self-attention, positional encoding, and layer normalization.
- **Trainable from Scratch**: Train the model on your own dataset.
- **Text Completion & Autocompletion**: Generates coherent and context-aware text.
- **Tokenization with GPT-2 Tokenizer**: Uses the pre-trained tokenizer from Hugging Face.
- **Training Pipeline**: Supports training on **CPU and GPU**.

## Model Architecture
The implementation consists of:
1. **Embedding Layer**: Converts tokenized input into dense vectors.
2. **Positional Encoding**: Adds sequential position information.
3. **Multi-Head Attention**: Enables contextual understanding of words.
4. **Feedforward Network**: Expands and contracts dimensions for non-linearity.
5. **Layer Normalization**: Stabilizes training.
6. **Output Layer**: Generates next token predictions.
