# Summarization in Different Ways

This repository contains an implementation of various text summarization techniques. The project demonstrates how to apply different methods to summarize text data, including extractive and abstractive approaches.

## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Methods](#methods)
- [Results](#results)
- [References](#references)
- [License](#license)

## Introduction
Text summarization is a process of creating a short and coherent version of a longer document. This project explores different techniques for text summarization, showcasing both extractive and abstractive methods.

## Requirements
- Python 3.6+
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- NLTK
- Gensim
- Transformers (Hugging Face)
- PyTorch or TensorFlow

## Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/summarization-in-different-ways.git
    cd summarization-in-different-ways
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To run the summarization techniques, follow these steps:

1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook summarization_in_different_ways.ipynb
    ```

2. Follow the instructions in the notebook to run the code cells. The notebook includes sections for:
    - Data loading and preprocessing
    - Applying different summarization techniques
    - Evaluating the results

## Methods
The notebook demonstrates various summarization methods, including:
- Extractive Summarization using clean and tokenization
- Extractive Summarization by calculating frequencies
- Abstractive Summarization using score_sentences
- defining the summarization function

## Results
The notebook provides examples and visualizations of the summarized texts. You can compare the results of different summarization techniques.

## References
- [A Survey of Text Summarization Techniques](https://arxiv.org/abs/1904.00688)
- [Text Summarization with Pretrained Encoders](https://arxiv.org/abs/1908.08345)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
