# Transformer Basics → Advanced Architectures

This repository is a hands-on learning space for understanding **Transformers** from first principles to modern, advanced model designs.

It is organized as a progressive journey:
- Start with core concepts (embeddings, positional encoding, attention)
- Build intuition with small, practical notebooks
- Move toward full encoder-decoder and decoder-only designs
- Explore efficient and advanced transformer architectures

---

## 📌 Current Content

- `1.0 Positional Embedding in Transformers.ipynb`  
	Introductory notebook explaining why sequence order matters and how positional information is injected into transformer inputs.

---

## 🧠 Learning Roadmap

### 1) Foundations
- Tokenization and embeddings
- Positional encodings (sinusoidal and learned)
- Scaled dot-product attention
- Multi-head attention intuition
- Residual connections and layer normalization

### 2) Core Transformer Blocks
- Encoder block internals
- Decoder block internals (masked self-attention)
- Feed-forward network behavior
- End-to-end encoder-decoder data flow

### 3) Training and Optimization
- Loss functions and teacher forcing
- Learning rate schedules and warmup
- Regularization: dropout, label smoothing
- Gradient stability and mixed precision basics

### 4) Decoder-Only LLM Style Models
- Causal attention and autoregressive generation
- KV caching
- Prompting basics and inference strategies

### 5) Advanced Architectures & Variants
- BERT, GPT, T5 family overview
- Vision Transformers (ViT)
- Efficient transformers (Longformer, Performer, Reformer, etc.)
- Sparse/linear attention ideas
- Mixture-of-Experts (MoE) concepts
- Retrieval-augmented transformers (RAG-style pipelines)

---

## 🗂️ Repository Structure

```text
Transformer_Basics/
├── 1.1 Positional Embedding in Transformers.ipynb
└── README.md
```

As new notebooks are added, they will follow a numbered sequence to keep the progression clear.

---

## ⚙️ Setup

### Prerequisites
- Python 3.9+
- Jupyter Notebook / JupyterLab / VS Code with Jupyter extension

### Create environment (recommended)

```bash
python -m venv .venv
```

Activate environment:

- **Windows (PowerShell):**
	```bash
	.venv\Scripts\Activate.ps1
	```
- **Windows (cmd):**
	```bash
	.venv\Scripts\activate.bat
	```
- **macOS/Linux:**
	```bash
	source .venv/bin/activate
	```

Install common dependencies:

```bash
pip install -U pip notebook jupyterlab numpy matplotlib torch
```

---

## ▶️ How to Use

1. Start Jupyter:
	 ```bash
	 jupyter notebook
	 ```
2. Open notebooks in numerical order.
3. Run cells top-to-bottom and inspect visualizations/outputs.
4. Modify hyperparameters and inputs to build intuition.

---

## 🎯 Goals of This Repository

- Build conceptual clarity, not just copy-paste implementations
- Connect math intuition to code behavior
- Progress from simple components to production-relevant architecture patterns
- Maintain reusable notebooks for revision and interview preparation

---

## 🛣️ Planned Notebook Sequence (Suggested)

- `1.0` Positional Embeddings ✅
- `1.1` Scaled Dot-Product Attention
- `1.2` Multi-Head Attention
- `1.3` LayerNorm + Residual Connections
- `2.0` Encoder Block from Scratch
- `2.1` Decoder Block from Scratch
- `2.2` Full Transformer (Toy Translation)
- `3.0` Training Loop, Scheduling, and Stability
- `4.0` GPT-Style Decoder-Only Model
- `5.0+` Advanced Architectures (BERT/T5/ViT/Efficient Transformers/MoE)

---

## 🤝 Contributions

This is a personal learning repository, but suggestions and improvements are always welcome:
- Better visual explanations
- Cleaner implementations
- New advanced architecture notebooks

---

## 📚 References

- *Attention Is All You Need* (Vaswani et al., 2017)
- The Annotated Transformer
- Hugging Face Transformers documentation
- PyTorch documentation

---

## ⭐ Note

If this repository helps your learning journey, consider starring it and sharing feedback on what topic should be added next.