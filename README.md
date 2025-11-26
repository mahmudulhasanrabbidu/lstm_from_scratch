# Custom-LSTM-TextGenerator From-Scratch

This repository contains a from-scratch implementation of a **multi-layer LSTM character-level language model**, built without using `nn.LSTM`.  
Every gate, weight matrix, and update step is implemented manually to show how LSTM works internally.

The project trains on raw text and generates new text **autoregressively** (character by character).

---

## 🚀 Features

- Complete **CharDataset** for character-level sequence modeling  
- Fully manual **MULTILayerLSTM** implementation (no PyTorch LSTM used)  
- Custom **CharRNN** wrapper  
- Clean training loop with **single epoch progress bar**  
- Proper **loss tracking per batch**  
- Autoregressive text generation  
- GPU support  
- From-scratch educational code structure

---
# 🏗️ Model Overview

### Key parts implemented from scratch:

- Input gate  
- Forget gate  
- Output gate  
- Candidate cell update  
- Multi-layer stacking  
- Full forward pass  
- Hidden state + Cell state flow  

This ensures you learn how LSTM works internally rather than treating it as a black box.

---

# 🧪 Goals of This Project

- Understand LSTM internals  
- Learn how multi-layer RNNs pass hidden states  
- Train a working character-level model  
- No shortcuts, no magical PyTorch layers  
- 100% educational and transparent  

---

# 🔧 Technologies Used

- Python  
- PyTorch  
- tqdm  
- NumPy  

---

# 🙌 Contributing

Pull requests, issues, and suggestions are welcome.  
This project is meant for learning — improvements benefit everyone.

---



i want to ad only these
