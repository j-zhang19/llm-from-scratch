
# LLM from Scratch

This project is an implementation of a GPT-style Large Language Model (LLM) built entirely from scratch, inspired by Sebastian Raschka’s book *Build a Large Language Model (From Scratch)*.
It walks through the full development pipeline: from tokenization to attention mechanisms, model architecture, pretraining, and fine-tuning.

---

## Structure

| Notebook                  | Description                                               |
|--------------------------------|-----------------------------------------------------------|
| `tokenizer.ipynb`              | Implements tokenization, sampling, and embeddings         |
| `attention.ipynb`              | Explores and implements the attention mechanism           |
| `gpt_model.ipynb`              | Builds the core GPT-style model architecture              |
| `pretraining.ipynb`            | Pretrains the model on unlabeled data                     |
| `finetuning.ipynb`             | Fine-tunes the model for classification tasks             |
| `instruction_finetuning.ipynb` | Fine-tunes the model for instruction-following tasks      |

---

## Installation

This project uses [uv](https://github.com/astral-sh/uv) for managing virtual environments and dependencies.

1. **Create a virtual environment:**

   ```bash
   uv venv
   source .venv/bin/activate
   ```

2. **Install dependencies:**

   ```bash
   uv pip install -r requirements.txt
   ```

3. **Verify the environment:**

   ```bash
   uv run python python_environment_check.py
   ```

---

## Reference

This project is based on the book:

<img src="https://camo.githubusercontent.com/54a738f9f8e7a0d8660d69a63af04c1f74b7c3059c349c78c29e545422ea73ad/68747470733a2f2f73656261737469616e72617363686b612e636f6d2f696d616765732f4c4c4d732d66726f6d2d736372617463682d696d616765732f636f7665722e6a70673f313233" width=400>

> Sebastian Raschka, *Build a Large Language Model (From Scratch)*

For more information, visit the [official repository](https://github.com/rasbt/LLMs-from-scratch).

---
