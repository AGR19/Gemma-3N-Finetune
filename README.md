# Fine-tuning Gemma-3N 
This project demonstrates how to fine-tune the `unsloth/gemma-3n-E2B-unsloth-bnb-4bit` model

## Why build this?

This project showcases the power of fine-tuning large language models on specific datasets to generate text in a particular style.

## Features

*   **Parameter-Efficient Fine-Tuning (PEFT):**  We use LoRA (Low-Rank Adaptation) for efficient fine-tuning, which significantly reduces the number of trainable parameters.
*   **Gemma-3 Chat Template:** The dataset is formatted using the Gemma-3 chat template for optimal performance with the model.
*   **Inference with the fine-tuned model:**  The notebook includes code for generating text with the fine-tuned model.
*   **Saving and sharing the model:**  The fine-tuned model is saved to the Hugging Face Hub for easy access and sharing.
*   **Merging LoRA adapters:** The LoRA adapters are merged with the base model to create a single, standalone model.

## Tech Stack

*   **Model:** `unsloth/gemma-3n-E2B-unsloth-bnb-4bit`
*   **Libraries:** `unsloth`, `transformers`, `peft`, `trl`, `datasets`, `torch`
*   **Platform:** Google Colab

## Getting Started

Follow these steps to run the project:

1.  **Open the notebook in Google Colab.**
2.  **Install the required libraries** by running the first code cell.
3.  **Load the pre-trained model and tokenizer.**
4.  **Prepare the model for fine-tuning** using PEFT and LoRA.
5.  **Load and format the dataset.**
6.  **Configure and start the training process.**
7.  **Perform inference with the fine-tuned model.**
8.  **Save the LoRA adapters and the merged model to the Hugging Face Hub.**
