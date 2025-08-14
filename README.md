# LoRA Multi-Dataset Fine-Tuning with BLEU & ROUGE Evaluation

## 📌 Overview
This project fine-tunes a Seq2Seq language model using **LoRA (Low-Rank Adaptation)** on **multiple datasets** for multi-task learning.  
It includes **custom preprocessing**, **multi-dataset handling**, **optimizer & scheduler setup**, and **evaluation** with BLEU and ROUGE scores.

---

## 🚀 Features
- Multi-dataset training (fitness + code feedback datasets)
- Task-specific prefixes for better multi-task learning
- LoRA fine-tuning for parameter-efficient training
- Custom optimizer (AdamW) & scheduler
- Checkpoint cleanup logic to save space
- BLEU & ROUGE evaluation metrics
- Inference examples included

---

## 📂 Datasets Used
- [Fitness Chat Prompt Completion Dataset](https://huggingface.co/datasets/chibbss/fitness-chat-prompt-completion-dataset)
- [Code Feedback Filtered Instruction](https://huggingface.co/datasets/m-a-p/CodeFeedback-Filtered-Instruction)

---

## 📦 Installation
```bash
pip install -r requirements.txt
