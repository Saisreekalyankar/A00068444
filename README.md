# Disempowerment Patterns in AI (Deep Learning Project)

## Overview
This project explores the concept of disempowerment in AI-generated responses. It implements a transformer-based classifier (BERT) combined with an RLHF-inspired reward mechanism to detect and mitigate distortion risks in language model outputs.

The system classifies responses into:
- Safe
- Mild Distortion
- High Distortion

A safety layer is applied to reduce high-risk outputs and promote neutral, user-aligned responses.

---

## Features
- BERT-based text classification model
- RLHF-inspired reward function
- Real-time safety intervention mechanism
- Evaluation using accuracy and F1-score
- Ablation study on reward parameter (Î»)

---

## Files
- code.ipynb â€“ Main implementation notebook
- report.pdf â€“ Final project report with methodology, results, and analysis

---

## Dataset
This project uses the *Anthropic HH-RLHF dataset*, which contains human-AI interaction data labeled for helpfulness and harmlessness.

Dataset link:  
https://huggingface.co/datasets/Anthropic/hh-rlhf

---

## Technologies Used
- Python
- PyTorch
- Transformers (Hugging Face)
- Google Colab

---

## How to Run
1. Open the notebook in Google Colab
2. Install required dependencies (if prompted)
3. Run all cells sequentially
4. View outputs and results within the notebook

## Author
Saisree Kalyankar