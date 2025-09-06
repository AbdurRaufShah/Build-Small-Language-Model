# Small Language Model (SLM) from Scratch

This project demonstrates how to build a **Small Language Model (SLM)** entirely from scratch using **PyTorch**.  
The notebook walks through dataset preparation, tokenization, model architecture, training, and inference.  
The goal is to understand how transformer-based language models work at a smaller, resource-efficient scale.

---

## 📑 Table of Contents
- [Overview](#overview)  
- [Features](#features)  
- [Project Structure](#project-structure)  
- [Quick Start](#quick-start)  
- [Requirements](#requirements)  
- [Usage](#usage)  
- [Motivation](#motivation)  
- [Acknowledgements](#acknowledgements)  
- [License](#license)  

---

## 🔎 Overview
This project builds a **transformer-based Small Language Model (SLM)** designed for efficient experimentation.  
The core implementation is in the notebook:  
**`Build_SLM_Model.ipynb`**

---

## 🚀 Features
- Tokenization of text data  
- Define model parameters (vocab size, hidden size, number of layers, etc.)  
- Training and evaluation loop  
- Efficient batch processing  
- Inference for text generation  

---

## 📂 Project Structure
- **`Build_SLM_Model.ipynb`** → Main Jupyter Notebook with full implementation.  

---

## ⚡ Quick Start
1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/SLM-Model.git
Open the notebook in Jupyter Notebook or VS Code.

Run the notebook cells step by step to preprocess data, train the model, and test text generation.


## 📦 Requirements
Python 3.8+

PyTorch

tqdm

matplotlib

Install the required libraries:
pip install torch tqdm matplotlib


## 🖥️ Usage
Open Build_SLM_Model.ipynb in your notebook environment and follow the steps:

Data preprocessing

Tokenization

Model definition (transformer-based SLM)

Training loop

Evaluation and text generation


## 🎯 Motivation
Large Language Models (LLMs) are powerful but computationally expensive.
This project explores how Small Language Models (SLMs) can be built to balance performance and efficiency, making them suitable for learning, research, and low-resource environments.


## 🙏 Acknowledgements
- Inspired by transformer-based models such as GPT and Gemma.  
- TinyStories dataset from HuggingFace, used for training and evaluation.  
- Thanks to the PyTorch community for tutorials and documentation. 


## 📜 License
This repository is for educational and research purposes only.
Please check dataset and library licenses before production use.
