# Text Generation with Recurrent Neural Networks (RNNs) and Transformers

![Python](https://img.shields.io/badge/python-v3.8-blue)
![TensorFlow](https://img.shields.io/badge/tensorflow-v2.7-orange)
![License](https://img.shields.io/badge/license-MIT-green)

This project focuses on generating text using Recurrent Neural Networks (RNNs) and Transformers implemented in TensorFlow. Various architectures such as GRU, LSTM, Bidirectional GRU, and transformers have been explored for text generation tasks.

## Overview

Text generation is a natural language processing task that involves generating coherent and contextually relevant sequences of text. RNNs and Transformers are popular choices for text generation due to their ability to capture sequential dependencies and long-range dependencies in the data.

## Implemented Architectures

1. **GRU (Gated Recurrent Unit)**: A type of RNN architecture that is more computationally efficient than LSTM (Long Short-Term Memory) networks while achieving similar performance in many tasks.

2. **LSTM (Long Short-Term Memory)**: An RNN architecture with additional memory cells and gating mechanisms to better capture long-term dependencies in sequential data.

3. **Bidirectional GRU**: A variant of GRU that processes input sequences in both forward and backward directions, enabling the model to capture contextual information from both past and future contexts.

4. **Transformers**: A class of models that use self-attention mechanisms to weigh the significance of different words in the input sequence, allowing them to capture long-range dependencies more effectively.
