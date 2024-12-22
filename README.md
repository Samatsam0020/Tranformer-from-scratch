# Transformer from Scratch

This repository contains a from-scratch implementation of several fundamental components of the Transformer architecture in Deep Learning. The goal is to understand and recreate the core mechanisms described in the groundbreaking paper *"Attention is All You Need"* by Vaswani et al.

## Implemented Features

The main components implemented in this project are:

- **Self-Attention**: Computing attention weights between words in a sequence.
- **Positional Encoding**: Adding positional information to preserve word order in sequences.
- **Encoder**: Encoding block comprising attention, feed-forward layers, and residual connections.
- **Decoder**: Decoding block similar to the encoder with an additional attention mechanism over the encoder's output.

## Repository Structure

- `notebooks/`: Contains Jupyter notebooks for each implemented component.

## Architecture Illustration

![Transformer Architecture](https://upload.wikimedia.org/wikipedia/commons/1/10/Transformer.png)

The image above illustrates the full Transformer architecture as described in the paper *"Attention is All You Need"*.

## References

- Vaswani, A., et al. (2017). *Attention Is All You Need*. [Link to the paper](https://arxiv.org/abs/1706.03762)


