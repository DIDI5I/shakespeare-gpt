# shakespeare-gpt
Transformer model trained on the Tiny Shakespeare dataset. Built from scratch in PyTorch with self-attention, multi-head attention, positional encoding, dropout, and feedforward layers.

## Overview
This project is a **Transformer-based language model** trained on the Tiny Shakespeare dataset.  
The goal was to implement core components of a Transformer from scratch in PyTorch and generate text in Shakespeare’s style.  

Currently, the implementation is contained in a **single file for simplicity**.  
Future updates will separate the code into:
- `model.py` → Transformer architecture
- `train.py` → Training loop with Adam + Cross-Entropy Loss
- `generate.py` → Text sampling script

---

## Features
- Implementation of:
  - Token embeddings
  - Self-attention & multi-head attention
  - Positional encodings
  - Feedforward layers
  - Dropout for regularization
- Training with Adam optimizer + Cross-Entropy Loss
- Text generation with greedy decoding
- Achieved training loss ~2.x (on limited hardware)

---

## Installation
```bash
git clone https://github.com/yourusername/shakespeare-gpt.git
cd shakespeare-gpt
pip install -r requirements.txt
