# Bidirectional LSTM — Sentiment Analysis of iPhone Reviews

This project implements a Bidirectional Long Short-Term Memory (BiLSTM)
model to classify Amazon iPhone reviews as Positive, Neutral, or Negative.

## Overview

The notebook covers the full pipeline: theory (SimpleRNN → LSTM → BiLSTM),
data preprocessing, model training, and evaluation — achieving 83.6% test accuracy.

## Contents

* `Bidirectional LSTM 24180169.ipynb` – main notebook
* `Bidirectional LSTM 24180169.pdf` – tutorial document
* `data/iphone.csv` – Amazon iPhone review dataset
* `requirements.txt` – pinned library versions for reproducibility

## How to Use

1. Clone this repository
git clone https://github.com/Sharranwijey15/Bidirectional-LSTM-24180169
2. Install required libraries
pip install -r requirements.txt
3. Open the notebook
jupyter notebook "Bidirectional LSTM 24180169.ipynb"
4. Run all cells from top to bottom

## Requirements

* Python 3.10 or 3.11 or 3.12 (recommended)
* TensorFlow 2.15 does not support Python 3.12
* All library versions are pinned in requirements.txt

## License

See the LICENSE file for details on permitted use.