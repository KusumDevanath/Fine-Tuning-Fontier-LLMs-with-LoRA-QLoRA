# Fine-Tuning Large Language Models with LoRA & QLoRA

## Overview
This project focuses on **parameter-efficient fine-tuning of Large Language Models (LLMs)** using **LoRA (Low-Rank Adaptation)** and **QLoRA (Quantized LoRA)** techniques. The objective is to adapt a pretrained LLM to a domain-specific enterprise dataset while minimizing computational cost, memory usage, and training time.

The project demonstrates how modern fine-tuning strategies enable organizations and researchers to customize powerful LLMs on limited hardware without full model retraining.

## Motivation
Traditional full fine-tuning of LLMs is computationally expensive and often infeasible for academic or enterprise environments. LoRA and QLoRA address this limitation by introducing trainable low-rank adapters while keeping the base model frozen.

This project was built to:
- Understand parameter-efficient fine-tuning techniques
- Fine-tune LLMs on domain-specific data
- Reduce GPU memory requirements using quantization
- Prepare production-ready, cost-efficient LLM pipelines

## Key Features
- LoRA-based fine-tuning of pretrained LLMs  
- QLoRA with 4-bit quantization for memory efficiency  
- Domain-specific dataset curation and preprocessing  
- Instruction-style data formatting  
- End-to-end training pipeline using PEFT techniques  
- Evaluation of model behavior before and after fine-tuning  

## System Workflow
1. **Data Curation** – Collection of domain-specific text data  
2. **Preprocessing** – Cleaning, tokenization, and instruction formatting  
3. **Base Model Loading** – Pretrained LLM loaded in quantized form  
4. **LoRA / QLoRA Adapters** – Injection of low-rank trainable adapters  
5. **Fine-Tuning** – Efficient training with frozen base weights  
6. **Inference & Evaluation** – Comparing base vs fine-tuned responses  

## Technologies Used
- Python  
- Hugging Face Transformers  
- PEFT (LoRA, QLoRA)  
- BitsAndBytes (4-bit quantization)  
- PyTorch  
- Jupyter Notebooks  

## Repository Structure
```
├── Data_Curation.ipynb
├── Data_Preprocessing.ipynb
├── FineTuning.ipynb
├── README.md
```

## Learning Outcomes
- Practical understanding of LoRA and QLoRA  
- Experience with quantized LLM training  
- Efficient fine-tuning on limited compute  
- Exposure to enterprise-ready LLM customization  

## Author
AI Master's Applicant | Aspiring AI Engineer
