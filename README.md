# Lightweight-FineTuning-GPT2

This repository demonstrates how to fine-tune a GPT-2 model for sentiment analysis using **Parameter-Efficient Fine-Tuning (PEFT)** techniques, specifically **LoRA (Low-Rank Adaptation)**. It includes steps for:
- Loading a pretrained GPT-2 model
- Fine-tuning using LoRA
- Evaluating and comparing the fine-tuned model's performance to the original model

## Features
- Uses the IMDB dataset for binary sentiment classification (Positive/Negative).
- Implements lightweight fine-tuning with LoRA for efficient training on limited hardware.
- Includes metrics for evaluation: Accuracy, Precision, Recall, and F1-score.
