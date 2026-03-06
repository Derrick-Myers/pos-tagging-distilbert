# POS Tagging with DistilBERT (Partial Freezing)

This project implements a Part-of-Speech (POS) tagging model using DistilBERT on the Universal Dependencies (UD) English dataset.

The experiment compares two training strategies:

1. Baseline fine-tuning (all layers trainable)
2. Partial freezing (freezing transformer layers)

## Results

Baseline Accuracy: 93.07%  
Frozen Model Accuracy: 85.11%  
Accuracy Drop: 7.96 percentage points

## Tools Used

- HuggingFace Transformers
- PyTorch
- Google Colab
- Universal Dependencies Dataset
