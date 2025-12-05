# Transformer Model

This repository was created as a hands-on way to study, build, and better understand Transformer architectures from the ground up.
The implementation loosely follows the excellent walkthroughs by **Andrej Karpathy**, using them as guidance to fully internalize the core concepts while still writing and experimenting with the code independently.

The project begins with a minimal **bigram language model** and progressively evolves into a full **Decoder-only Transformer**, including multi-head self-attention, positional embeddings, feed-forward layers, and residual connections—mirroring the architecture described in the _Attention Is All You Need_ paper.

> **Note**
> This implementation focuses on a **Decoder-only** model (similar to GPT-style architectures).
> Therefore, it does **not** include the Encoder module or the cross-attention (Encoder-Decoder Attention) block.

---

## 📘 Notebooks

- **`simple_bigram.ipynb`**
  Introduces the fundamental components behind language modeling and builds a simple bigram model to set the foundation for understanding attention.

- **`matrix_example_attention.ipynb`**
  Demonstrates core attention operations using small, interpretable matrix examples. This helps visualize how queries, keys, and values interact.

- **`transformer_model.ipynb`**
  Implements a full Transformer Decoder block step-by-step, including multi-head self-attention, feed-forward networks, residual connections, and layer normalization.

---

Feel free to explore, modify, and experiment—this repo is meant for learning and tinkering!
