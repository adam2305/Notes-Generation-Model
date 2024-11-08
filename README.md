# 🎶 Music Generation with LSTM and Transformer Models

This project presents a generative AI model for music creation, trained on MIDI files to produce sequences of musical notes. It explores two powerful approaches — LSTM (Long Short-Term Memory) and Transformer models — to generate music that mimics the style and structure of the training data.

## Project Overview

The goal of this project is to generate coherent, original musical compositions by learning from patterns in existing music. Using sequences of MIDI-encoded notes, the models are trained to recognize musical structures and generate new compositions when sampled.

## Key Components

- Data Processing: Parses MIDI files to extract note sequences suitable for model training.
- LSTM Model: Utilizes a recurrent neural network that remembers previous notes to predict subsequent ones, generating sequences with a sense of musical flow.
- Transformer Model: Uses attention mechanisms to capture long-term dependencies in the music, enabling more intricate and complex compositions.

## Usage
Run the training scripts to train either the LSTM or Transformer model and generate new music by sampling from the trained models. This setup provides a baseline for experimenting with AI-driven music composition and is flexible for further development.


