# LoRA-Summarizer

This guide shows you how to fine-tune language models for summarizing text using a technique called LoRA (Low-Rank Adaptation). We’ll use the T5 and BART-large-cnn models and the SAMSum dataset to train these models in a single Jupyter Notebook.

  

# Use LoRA for efficient model fine-tuning.
Train T5 and BART-large-cnn models for summarization with the SAMSum dataset.
Save the trained model to the Hugging Face model hub.
Load and use the model for making predictions.


# Dataset Details
Training Data: 14,732 samples
Validation Data: 818 samples
Test Data: 819 samples
Data Fields
dialogue: The chat text.
summary: The summary of the chat.
id: A unique identifier for each example.


# Example
json

{
  "id": "13818513",
  "summary": "Amanda baked cookies and will bring Jerry some tomorrow.",
  "dialogue": "Amanda: I baked cookies. Do you want some?\r\nJerry: Sure!\r\nAmanda: I'll bring you tomorrow :-)"
}
How to Get Started
Requirements
Make sure you have Python and these packages:

transformers
torch
datasets
