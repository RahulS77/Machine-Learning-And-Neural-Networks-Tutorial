# Machine-Learning-And-Neural-Networks-Tutorial
Attention Mechanisms: Elevating News Topic Classification Beyond LSTMs

## How to Run It
### Open in Colab
- **Download** `Elevating_News_Topic_Classification_Beyond_LSTMs.ipynb` from this repo.
- **Upload** to Google Colab via **"File > Upload Notebook"**.
- Or, click this badge:  
  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1j0QdCWvNHoupuXRcFe3eZGEDnxoA5b9i?usp=sharing)

### Run It
- Hit **"Runtime > Run All"** (or `Ctrl+F9`)
- Takes ~5-10 minutes(depends on Colab's free GPU/CPU)

### Outputs
- `accuracy.png` (containing **Accuracy: Vanilla vs. Attention LSTM**) and `attention_weights.png` (containing Attention Weights)
- Final accuratcies print in the last cell- expect ~52% Vanilla and 75% Attention, slight variance is ok.

### Requirements
- No install needed-Colab proloads TensorFlow, Matplotlib, Numpy
- Ensure Colab's runtime is Python 3 (default).
