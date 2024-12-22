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

![Transformer Architecture](https://www.google.com/imgres?q=transformers%20architecture%20deep%20learning&imgurl=https%3A%2F%2Fmachinelearningmastery.com%2Fwp-content%2Fuploads%2F2021%2F08%2Fattention_research_1.png&imgrefurl=https%3A%2F%2Fmachinelearningmastery.com%2Fthe-transformer-model%2F&docid=8BFEFEH368UfNM&tbnid=vX3-oFwpHiwA2M&vet=12ahUKEwifgJSpxLuKAxUSU0EAHXG3IMQQM3oECBYQAA..i&w=1320&h=1860&hcb=2&ved=2ahUKEwifgJSpxLuKAxUSU0EAHXG3IMQQM3oECBYQAA))

The image above illustrates the full Transformer architecture as described in the paper *"Attention is All You Need"*.

## References

- Vaswani, A., et al. (2017). *Attention Is All You Need*. [Link to the paper](https://arxiv.org/abs/1706.03762)


