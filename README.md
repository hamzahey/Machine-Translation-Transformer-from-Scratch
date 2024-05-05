# Build Your Own Machine Translation Transformer from Scratch

Welcome to this project where we will embark on a journey to build a machine translation transformer from scratch. Follow along as we implement key components step by step!

## Project Overview

This project aims to build a machine translation transformer model entirely from scratch using TensorFlow. We will cover fundamental components of the transformer architecture, including positional encoding, multi-head attention, feed-forward networks, encoder blocks, decoder blocks, and the complete transformer model.

## Project Roadmap

- [ ] **Positional Encoding**: Implement the positional encoding mechanism to inject positional information into token embeddings.
- [ ] **Multi Head Attention**: Build the multi-head attention layer to compute attention scores across different heads.
- [ ] **Feed Forward Network**: Create the feed-forward network layer used within transformer blocks.
- [ ] **Encoder Block**: Develop the encoder block consisting of multi-head attention and feed-forward network.
- [ ] **Decoder Block**: Construct the decoder block with multi-head attention, encoder-decoder attention, and feed-forward network.
- [ ] **Transformer**: Combine encoder and decoder blocks to form the complete transformer architecture.
- [ ] **Model Training**: Implement the training loop to train the machine translation transformer.

## Implementation Details

- **Positional Encoding**: Use sinusoidal positional encoding to represent the position of tokens in the sequence.
- **Multi Head Attention**: Implement scaled dot-product attention with multiple attention heads.
- **Feed Forward Network**: Create a two-layer feed-forward neural network with ReLU activation.
- **Encoder Block**: Construct the encoder block with multi-head attention and position-wise feed-forward network.
- **Decoder Block**: Build the decoder block with multi-head attention, encoder-decoder attention, and position-wise feed-forward network.
- **Transformer**: Assemble the transformer model using multiple encoder and decoder blocks.
- **Model Training**: Implement the training loop with custom learning rate scheduling and optimization.

## Dependencies

This project requires the following dependencies:

- TensorFlow 2.x
- NumPy
- Matplotlib
- (Optional) Hugging Face transformers (for comparison and testing)