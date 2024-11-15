# Machine Translation with mT5

This project involves training a multilingual sequence-to-sequence (seq2seq) neural network for language translation using the mT5 model from Hugging Face's transformers library. The dataset used is the ALT dataset, which includes translations in multiple languages.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
  - [Dataset Preparation](#dataset-preparation)
  - [Tokenizer and Model Initialization](#tokenizer-and-model-initialization)
  - [Training](#training)
  - [Evaluation](#evaluation)
  - [Saving the Model](#saving-the-model)
- [Acknowledgements](#acknowledgements)

## Introduction
The goal of this project is to create a neural translation model that can translate between multiple languages. The model is based on the mT5 transformer architecture, which is designed for multilingual text generation tasks. The project includes data loading and preprocessing, model training, evaluation, and saving the trained model.

## Installation
To get started, clone this repository and install the required packages. Ensure you have the necessary Python packages such as:

- transformers
- sentencepiece
- datasets
- ipywidgets
- keras
- torch
- torchvision
- torchaudio

You can install the dependencies by running:

```bash
pip install -r requirements.txt
