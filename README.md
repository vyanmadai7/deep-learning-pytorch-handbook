# 🔥 PyTorch Masterclass — Zero to Research Engineer

> A complete, textbook-grade PyTorch course for engineers who know TensorFlow
> and want to reach FAANG / research-level proficiency fast.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python 3.8+](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
[![PyTorch 2.0+](https://img.shields.io/badge/PyTorch-2.0+-ee4c2c.svg)](https://pytorch.org)
[![Stars](https://img.shields.io/github/stars/YOUR_USERNAME/pytorch-masterclass?style=social)](https://github.com/YOUR_USERNAME/pytorch-masterclass)

---

## 📖 What This Is

A single, self-contained reference that covers everything from
`torch.tensor()` to multi-GPU training and production deployment —
structured like a university course with inline code labs.

**Who it's for:** ML engineers who know TensorFlow/Keras and want a
fast, no-fluff transition to PyTorch at a professional level.

---

## 📚 Contents — 20 Chapters

| # | Chapter | Key Concepts |
|---|---------|-------------|
| 01 | PyTorch vs TensorFlow | Mental model mapping, dynamic graphs |
| 02 | Tensors | Creation, shape ops, GPU, broadcasting |
| 03 | Autograd & Computation Graph | requires_grad, DAG, no_grad, detach |
| 04 | Backpropagation | Manual + automatic, custom autograd |
| 05 | nn.Module | Model building, train/eval, init |
| 06 | Layers Deep Dive | Linear, Conv2d, LSTM, Embedding, Norms |
| 07 | Loss Functions & Optimizers | CE, BCE, AdamW, schedulers, clipping |
| 08 | Training Loop | 5-step loop, AMP, early stopping |
| 09 | DataLoader & Dataset | Custom datasets, transforms, samplers |
| 10 | GPU Training / CUDA | AMP, DDP, torch.compile, profiling |
| 11 | CNN from Scratch | ResNet, residual blocks, CIFAR-10 |
| 12 | RNN / LSTM | Sequence modeling, attention, Seq2Seq |
| 13 | Transfer Learning | Feature extraction, fine-tuning, BERT |
| 14 | Custom Projects | Transformer from scratch, multi-head attn |
| 15 | Debugging Training | Gradient flow, hooks, NaN detection |
| 16 | Save / Load Models | state_dict, checkpoints, ONNX, TorchScript |
| 17 | PyTorch Lightning | LightningModule, Trainer, callbacks |
| 18 | Real Projects | Image classifier + NLP sentiment model |
| 19 | Industry Best Practices | EMA, WandB, profiling, code structure |
| 20 | Job-Ready Roadmap | 30-day sprint, project checklist |

---

## 🚀 Quick Start

```bash
# Clone
git clone https://github.com/YOUR_USERNAME/pytorch-masterclass.git
cd pytorch-masterclass

# Open the interactive reference
open pytorch_masterclass.html   # macOS
# or just open in any browser
```

To run the code examples:

```bash
pip install torch torchvision torchaudio
# GPU (CUDA 12.1)
pip install torch torchvision torchaudio \
    --index-url https://download.pytorch.org/whl/cu121
```

---

## 🗂️ Repository Structure
pytorch-masterclass/<br>
├── pytorch_masterclass.html    # Complete interactive reference (open in browser)<br>
├── notebooks/<br>
│   ├── 01_tensors.ipynb<br>
│   ├── 02_autograd.ipynb<br>
│   ├── 03_training_loop.ipynb<br>
│   ├── 04_cnn_cifar10.ipynb<br>
│   ├── 05_lstm_sentiment.ipynb<br>
│   ├── 06_transformer_scratch.ipynb<br>
│   └── 07_bert_finetuning.ipynb<br>
├── src/<br>
│   ├── models/<br>
│   │   ├── resnet.py           # ResNet from scratch<br>
│   │   ├── lstm_classifier.py  # BiLSTM sentiment model<br>
│   │   └── transformer.py      # Transformer from scratch<br>
│   ├── training/<br>
│   │   ├── train_cifar10.py    # ~93% accuracy pipeline<br>
│   │   └── train_bert.py       # BERT fine-tuning<br>
│   └── utils/<br>
│       ├── checkpoint.py<br>
│       └── reproducibility.py<br>
├── configs/<br>
│   └── cifar10_resnet.yaml<br>
├── requirements.txt<br>
└── README.md<br>


---

## 📊 What You'll Build

| Project | Architecture | Dataset | Target Accuracy |
|---------|-------------|---------|----------------|
| Image Classifier | ResNet + Mixup | CIFAR-10 | **~93%** |
| Sentiment Analysis | BiLSTM | IMDB | **~92%** |
| Text Classifier | Transformer | SST-2 | **~91%** |
| BERT Fine-tuning | bert-base-uncased | SST-2 | **~95%** |

---

## 🔑 Key Differentiators

- **TF→PT mapping table** — exact concept equivalents for every TF API
- **Internals explained** — not just how, but *why* each piece works
- **Production patterns** — code structured like real FAANG ML pipelines
- **Debugging toolkit** — gradient checks, hooks, NaN scanners, profiling
- **Complete exercises** — mini challenges after every chapter

---

## 📋 Requirements
torch >= 2.0<br>
torchvision >= 0.15<br>
pytorch-lightning >= 2.0<br>
transformers >= 4.30<br>
numpy<br>
Pillow<br>
wandb          # optional, for experiment tracking<br>

---

## 🗺️ Learning Path
Week 1  →  Chapters 1-4   (Fundamentals)
Week 2  →  Chapters 5-8   (Core Framework)
Week 3  →  Chapters 9-12  (Architecture Builds)
Week 4  →  Chapters 13-16 (Advanced + Production)
Week 5  →  Chapters 17-20 (Lightning, Real Projects, Roadmap)

---

## 🤝 Contributing

Contributions welcome! Areas that need work:

- [ ] Jupyter notebooks for each chapter
- [ ] Runnable Python scripts for all code examples
- [ ] Add diffusion model chapter
- [ ] Add LoRA / PEFT fine-tuning section
- [ ] Add TorchServe deployment chapter

Please open an issue before submitting a large PR.

---

## 📄 License

MIT — use freely, attribution appreciated.

---

## ⭐ Star History

If this helped you, a star means more engineers can find it.

---

*Built with the goal that every ML engineer should be able to move
between frameworks fluently. PyTorch is where research happens —
this is your bridge.*
