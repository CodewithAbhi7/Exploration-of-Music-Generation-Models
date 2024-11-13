# Exploration of Music Generation Models

This project explores various music generation models, including autoregressive, CNN, GAN, GRU, LSTM, RNN, Seq2Seq, Transformer, and VAE-based approaches. Each model is implemented and tested in Python to evaluate its effectiveness in generating music sequences. 

## Table of Contents
- [Project Overview](#project-overview)
- [Files](#files)
- [Installation](#installation)
- [Usage](#usage)
- [Note](#note)
- [Acknowledgments](#acknowledgments)

## Project Overview

Music generation models are designed to generate coherent musical sequences, simulating patterns learned from a dataset of music. This project implements several different types of models, each with its unique architecture and approach to generating music. The models range from simpler RNNs to more complex GAN and Transformer-based architectures. Each model is saved as a Jupyter Notebook for easy experimentation and modification.

## Files

Here are the main files in this project:

- **Autoregressive_Music_Generation.ipynb** - Autoregressive model for generating music.
- **CNN_Music_Generation.ipynb** - Convolutional Neural Network (CNN) model for music generation.
- **GAN_Music_Generation.ipynb** - Generative Adversarial Network (GAN) model for generating music.
- **GRU_Music_Generation.ipynb** - Gated Recurrent Unit (GRU) model for music generation.
- **LSTM_Music_Generation.ipynb** - Long Short-Term Memory (LSTM) model for generating music sequences.
- **RNN_Music_Generation.ipynb** - Recurrent Neural Network (RNN) model for music generation.
- **Seq2Seq_Music_Generation.ipynb** - Sequence-to-Sequence (Seq2Seq) model for generating music sequences.
- **Transformer_Music_Generation.ipynb** - Transformer model for music generation.
- **VAE_Music_Generation.ipynb** - Variational Autoencoder (VAE) model for generating music.

## Installation
just open this notebook in Google colab, simple ☺️

## Note 
- This study primarily focuses on the exploration of various models that can be used for music generation and their structure rather than aiming to achieve their best possible performance. Due to limited GPU resources and the exploratory nature of this study, the reported results may not fully reflect the models’ optimal performance. The analysis was conducted using simple model structures within TensorFlow to explore how these models can be applied to music generation. With fine-tuning and additional computational power, many of these models could be better optimized for tasks such as polyphonic music generation and chord prediction. These models are generated for research purposes, and a research paper based on this work will be published soon.

## Acknowledgments
This project was inspired by the work from [@aamini](https://github.com/aamini) and at [aamini/introtodeeplearning](https://github.com/aamini/introtodeeplearning), specifically the music generation implementation found [here](https://github.com/aamini/introtodeeplearning/blob/master/lab1/Part2_Music_Generation.ipynb). We extend our thanks for the foundational code provided, which helped build and shape the models in this project.
