# Mini-GPT Transformer from Scratch

This repository contains an implementation of the core ideas from the research paper **“Attention Is All You Need”**, written entirely in PyTorch without relying on prebuilt Transformer modules.  
It’s a small, decoder-only (GPT-style) language model with about **8 million parameters** trained at the **character level** on the entire **The Lord of the Rings** Novel.

## Transformer Architecture
A standard Encoder-Decoder Transformer architecture.

![Transformer Architecture](https://github.com/user-attachments/assets/178cfa67-73e9-45fe-b0f5-74620b108744)


## Output Snippet
Because of the small size of the model, and it being only pre-trained, outputs are not always coherent, but it’s a useful learning tool for understanding how GPT-style models work internally.

<img width="690" height="424" alt="Snippet story" src="https://github.com/user-attachments/assets/91c264d6-212a-4adb-bcef-4887552d1247" />


## Usage

Clone the repo and install dependencies:

```bash
pip install torch==2.8.0
```

Run the jupyter notebook:

```bash
jupyter gpt_from_scratch.ipynb
```



