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


---

### 3️⃣ Model Architecture
The model follows a **GPT-style decoder-only design**:

- Token Embedding Layer
- Positional Encoding
- Multiple Transformer Decoder Blocks
- Causal Self-Attention
- Linear Output Layer over vocabulary

Causal masking ensures the model only attends to **past tokens**.

---

### 4️⃣ Training Process
- Autoregressive training objective
- Cross-entropy loss
- Batch-wise training using shuffled reviews
- The model learns to predict the next word given previous words

---

### 5️⃣ Text Generation
After training, the model can generate text by:
1. Providing an initial prompt
2. Predicting the next token
3. Feeding the prediction back into the model
4. Repeating until completion

---


---

## 📚 Key Concepts Learned
- Decoder-only Transformers
- Causal Attention Masks
- Autoregressive Language Modeling
- Token Embeddings & Positional Encoding
- Text Generation using Neural Networks

---

## 📈 Learning Outcome
By completing this lab, you will:
- Understand how GPT-like models generate text
- Learn why decoders are used for language modeling
- Gain hands-on experience with Transformer internals
- Be able to adapt the model for other NLP tasks

---

## 🔮 Future Improvements
- Use subword tokenization (BPE / WordPiece)
- Increase model depth and attention heads
- Train on larger corpora
- Fine-tune for sentiment classification or instruction following

---

## 🏫 Course Information
**Generative AI Language Modelling With Transformers IBM**  
Decoder-Based Language Modeling Lab (IMDb Dataset)

---

