# ScratchGPT

> **⚠️ Currently Under Development**

**ScratchGPT** is a learning-focused implementation project aimed at understanding and building a **GPT-like large language model from scratch** using PyTorch.

This repository follows a hands-on, from-first-principles approach inspired by the educational work and open-source materials shared by **Sebastian Raschka**.  
Reference materials and related resources can be found on his GitHub: https://github.com/rasbt

The primary objective of this project is to deeply understand the internal mechanics of modern language models by explicitly implementing each major component with minimal abstraction.

---

## Project Structure

The repository is organized into modular components that reflect the full large language model pipeline:
```
ScratchGPT/
│
├── preprocess/      # Text cleaning, tokenization, vocabulary building
│
├── pretrain/        # Language model training (decoder-only transformer)
│
├── finetune/        # Task-specific fine-tuning
│
├── appendix/        # Supporting material (PyTorch basics, neural network foundations)
│
├── notebooks/       # Experiments and exploratory work
│
├── utils/           # Shared utilities and helper functions
│
└── README.md
```

---

## Key Concepts Covered

- Text preprocessing and tokenization  
- Vocabulary construction and token-to-ID mapping  
- Embedding layers  
- Decoder-only transformer architecture  
- Self-attention and feed-forward networks  
- Autoregressive language modeling  
- Loss computation and optimization  
- Fine-tuning workflows  

---

## Design Philosophy

- **Learning-oriented**: Focused on understanding model internals rather than performance or scale  
- **From scratch**: Core ideas are implemented explicitly instead of relying on high-level abstractions  
- **Modular**: Each stage of the pipeline is isolated and reusable  
- **Readable**: Code prioritizes clarity and correctness  

---

## Tech Stack

- Python  
- PyTorch  
- NumPy  
- Standard scientific Python ecosystem  

---

## Acknowledgements

This project is inspired by and follows educational material created by **Sebastian Raschka**.  
All credit for the underlying concepts and teaching approach belongs to the original author.

---