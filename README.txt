# Lightweight Fine-Tuning of GPT-2 with LoRA

This project demonstrates parameter-efficient fine-tuning (PEFT) of the GPT-2 model for sentiment classification on the IMDb dataset using the LoRA technique and Hugging Face's `peft` library.

## Project Overview

The project includes:

- Loading and evaluating a pre-trained GPT-2 model.
- Performing LoRA-based fine-tuning using PEFT.
- Running inference with the fine-tuned model.
- Comparing performance between the original and fine-tuned models.

## Tools and Libraries

- PyTorch
- Hugging Face Transformers
- Hugging Face PEFT
- IMDb dataset

## Dataset

- IMDb (via [Hugging Face Datasets library](https://huggingface.co/datasets/stanfordnlp/imdb))

## Fine-Tuning Technique

- PEFT: LoRA (Low-Rank Adaptation)

## Model

- GPT-2

## Evaluation

- Using the `evaluate` method with Hugging Face's `Trainer`.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/leticiazorzirama/peft-lora-gpt2-imdb.git
   cd peft-lora-gpt2-imdb
