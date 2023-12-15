# LLM Fine-Tuning Using QLoRA on Intel GPUs - MVP Codebase

## Overview
This repository contains a minimal viable product (MVP) for fine-tuning Large Language Models (LLMs) using Quantized Low Rank Adaptation (QLoRA) in 4 bits on Intel GPUs. The code demonstrates how to port a model from Nvidia to Intel GPUs, focusing on simplicity.

### Features
- **LLM Loading and Training**: Loads the "NousResearch/Nous-Hermes-Llama-2-7b" LLM model and fine-tunes it using the PEFT library from Hugging Face 🤗.
- **Intel Developer Cloud Integration**: Designed to run seamlessly on the Intel Developer Cloud (IDC) platform.
- **Reference for Nvidia GPUs**: Includes a reference for running similar training on Nvidia GPUs on Google Collab.

## Getting Started
Clone the repository and follow the instructions in the Jupyter Notebook to set up and run the model fine-tuning process. Ensure you have access to Intel GPUs.

## Additional Resources
- For a more extensive tutorial on fine-tuning LLMs using this approach on Intel® Data Center GPU Max 1100, check out the **LLM Finetuning notebook** under **"GenAI Essentials"** on IDC.
- Nvidia GPU training reference: [Google Colab Notebook](https://colab.research.google.com/drive/1H1SHcmYrHiHtAIJwMXT4E7dhXDLqvGtr?usp=sharing).
