# 🧠 GPT-Like Decoder Model for Text Generation using IMDb Dataset

## 📌 Overview
This project focuses on building and training a **decoder-only (GPT-like) Transformer model** using the **IMDb movie reviews dataset**.  
The primary objective is to understand how **autoregressive language models** work by training the model to predict the **next token** in a sequence.

Although the IMDb dataset is commonly used for sentiment analysis, in this lab it is used as **raw text** to train a **text generation model**.

---

## 🎯 Objectives
- Understand the **decoder-only Transformer architecture**
- Learn how **causal self-attention** enables text generation
- Perform **tokenization and numerical encoding** of text
- Train a model using **next-token prediction**
- Generate text learned from IMDb movie reviews

---

## 🗂️ Dataset: IMDb Movie Reviews
- Contains **50,000 movie reviews**
- Each review is written in natural language
- Used here **without sentiment labels**
- Reviews are treated as independent text samples

The dataset is ideal for learning language structure, grammar, and writing style.

---

## 🛠️ Technologies Used
- Python
- PyTorch
- TorchText
- NumPy
- Transformer (Decoder-only)

---

## 🔄 Project Workflow

### 1️⃣ Environment Setup
- Install required libraries
- Configure PyTorch and TorchText
- Set up training and validation pipelines

---

### 2️⃣ Data Preparation
- Load IMDb reviews
- Tokenize text into tokens
- Convert tokens into integer IDs
- Create input-target pairs for next-token prediction

Example:
