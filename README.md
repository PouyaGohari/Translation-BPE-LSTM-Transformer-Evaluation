# Translation-BPE-LSTM-Transformer-Evaluation
This repository implements English-to-Persian translation using Fairseq. It covers BPE tokenization, LSTM and Transformer models, and evaluation with BLEU and COMET scores. This project is part of a Natural Language Processing course assignment at the University of Tehran.

## Table of Contents

- [Introduction](#introduction)
- [Assignment Overview](#assignment-overview)
- [Dataset](#dataset)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Evaluation](#evaluation)
- [Results and Analysis](#results-and-analysis)
- [Report](#report)
- [License](#license)

## Introduction

This project focuses on building translation models from English to Persian using the Fairseq library. The work includes training a BPE tokenizer with SentencePiece, followed by training LSTM and Transformer models. The models are evaluated using BLEU and COMET scores to assess their translation quality.

## Assignment Overview

### Part 1: BPE Tokenization with SentencePiece

- Train a BPE (Byte-Pair Encoding) tokenizer using the SentencePiece library.
- Tokenize the dataset using the trained BPE model and prepare it for training with Fairseq.

### Part 2: Training Translation Models

1. **LSTM Model:**
   - Train an LSTM model for English-to-Persian translation using the Fairseq library.
2. **Transformer Model:**
   - Train a Transformer model for the same translation task using Fairseq.

### Part 3: Evaluation and Analysis

- **Evaluation Metrics:**
  - Evaluate the performance of the LSTM and Transformer models using BLEU and COMET scores.
  - Analyze and compare the results based on these metrics.

## Dataset

The dataset used for training and evaluation is the English-Persian parallel corpus from the OPUS-MIZAN project. You can download the dataset from the following link:

- **Dataset:** [OPUS-MIZAN English-Persian Corpus](https://object.pouta.csc.fi/OPUS-MIZAN/v1/moses/en-fa.txt.zip)

## Prerequisites

Before you begin, ensure you have the following requirements:
- Libraries: `fairseq`, `sentencepiece`, `sacremoses`, `unbabel-comet`
- Basic understanding of NLP concepts, especially tokenization, LSTM, and Transformer models.


## Installation

To clone and run this repository locally:
```sh
git clone https://github.com/PouyaGohari/Translation-BPE-LSTM-Transformer-Evaluation.git
cd Translation-BPE-LSTM-Transformer-Evaluation
```

## Usage
## Usage

This project is implemented in a single Jupyter notebook:

- **Notebook:** [`CA5_FINAL.ipynb`](CA5_FINAL.ipynb)

To run the project:

1. Open the `CA5_FINAL.ipynb` notebook.
2. Follow the instructions to preprocess the data, train the models (LSTM and Transformer), and evaluate their performance with BLEU and COMET scores.

The notebook is self-contained, with detailed instructions and code explanations for each step of the process.

## Evaluation

The models are evaluated using the following metrics:

- **BLEU Score:** A metric for evaluating the quality of the translated text.
- **COMET Score:** An advanced evaluation metric using the COMET model from Unbabel, providing nuanced insights into translation quality.

## Results and Analysis

- **BPE Tokenization:** Analysis of how BPE tokenization affects the model’s performance.
- **LSTM vs. Transformer:** Comparison of the translation quality between the LSTM and Transformer models.
- **BLEU vs. COMET:** Discussion on the differences between BLEU and COMET scores and their implications for evaluating translation models.

## Report

A comprehensive report detailing the research, methodology, implementation, results, and analysis for each part of the assignment is available [here](NLP_CA5.pdf).

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE)
