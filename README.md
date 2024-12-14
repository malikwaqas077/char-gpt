# Char-GPT

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff&style=flat-square) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=fff&style=flat-square) ![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?logo=google-colab&logoColor=fff&style=flat-square)

This repository contains a GPT-like language model built using PyTorch. The model is trained on character-level data and utilizes a multi-head self-attention mechanism, inspired by transformer architecture.

## Features

- Character-level language modeling.
- Implements self-attention with multiple heads.
- Supports positional embeddings.
- Configurable hyperparameters for training and evaluation.

## Model Architecture

- Multi-head Self-Attention
- Feed-Forward Neural Network
- Transformer Blocks
- Embedding Layers for Tokens and Positions

## Requirements

- Python 3.8+
- PyTorch

## Installation

1. Clone the repository:

```bash
git clone https://github.com/malikwaqas077/char-gpt.git
cd char-gpt
```

2. Install dependencies:

```bash
pip install torch
```

## Usage

### Training the Model

1. Download the input dataset (e.g., Shakespeare text) and save it as `input.txt`.

2. Run the script to train the model:

```bash
python train.py
```

### Generating Text

To generate text using the trained model, execute:

```bash
python generate.py
```

## Hyperparameters

The hyperparameters can be adjusted in the script. Key parameters include:

- `batch_size`: Number of sequences processed in parallel.
- `block_size`: Maximum context length for predictions.
- `n_embd`: Embedding size.
- `n_head`: Number of attention heads.
- `n_layer`: Number of transformer layers.

## Example Output

Once trained, the model generates text based on the character-level input:

```
Generated text sample...
```

## Frameworks and Tools Used

- [PyTorch](https://pytorch.org/) for deep learning.
- [Google Colab](https://colab.research.google.com/) for interactive development and training.

## Contribution

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
