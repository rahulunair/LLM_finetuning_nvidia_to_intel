# LLM Fine-Tuning Using QLoRA on Intel GPUs - MVP Codebase

## Overview
This repository contains an MVP example on fine-tuning Large Language Models (LLMs) using Quantized Low Rank Adaptation (QLoRA) in 4 bits on Intel GPUs. The code demonstrates how to port a model from Nvidia to Intel GPUs, focusing on simplicity.

For more extensive examples on running GenAI workloads on Intel GPUs, checkout this [repo](https://github.com/rahulunair/GenAI).

### Features
- **LLM Loading and Training**: Loads the "NousResearch/Nous-Hermes-Llama-2-7b" LLM model and fine-tunes it using the PEFT library from Hugging Face 🤗.
- **Intel Developer Cloud Integration**: Designed to run seamlessly on the [Intel Developer Cloud](https://cloud.intel.com) (IDC) platform.
- **Reference for Nvidia GPUs**: Includes a reference for running similar training on Nvidia GPUs on Google Collab.

## Getting Started
Clone the repository and follow the instructions in the Jupyter Notebook to set up and run the model fine-tuning process. Ensure you have access to Intel GPUs.

## Additional Resources
- For a more extensive tutorial on fine-tuning LLMs using this approach on Intel® Data Center GPU Max 1100, check out the **LLM Finetuning notebook** under **"GenAI Essentials"** on IDC.
- Nvidia GPU training reference: [Google Colab Notebook](https://colab.research.google.com/drive/1H1SHcmYrHiHtAIJwMXT4E7dhXDLqvGtr?usp=sharing).

## 🚀 Geeky Stats Alert! 🎨

Rough time taken for finetuning LLMs using QLoRA using the alpaca dataset for LLama2 7b and LLama2 70b models:

![llama2_7b_fine_tuning_time](https://github.com/rahulunair/LLM_finetuning_nvidia_to_intel/assets/786476/7cb46a8d-857c-4e35-a293-b136387feaff)
![llama2_70b_fine_tuning_time](https://github.com/rahulunair/LLM_finetuning_nvidia_to_intel/assets/786476/8eaba36a-ed82-4d0d-9f27-99bcbff5f8ac)
