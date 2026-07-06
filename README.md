# Domain-Specific Fine-Tuning of Open-Source Large Language Models

This project explores multiple approaches for adapting open-source Large Language Models (LLMs) to specialized domains using parameter-efficient fine-tuning techniques. The work includes continued pretraining, instruction tuning, and domain-specific adaptation across different datasets.

---

## Overview

The objective of this project was to understand different strategies for improving pretrained language models without training them from scratch.

The project investigates:

- Continued pretraining on domain-specific corpora
- Instruction tuning using conversational datasets
- Domain adaptation for specialized language
- Parameter-efficient fine-tuning using LoRA

---

## Project Structure

```
.
├── notebooks/
│   ├── continued_pretraining.ipynb
│   ├── instruction_tuning.ipynb
│   └── financial_domain_adaptation.ipynb
│
├── README.md
└── requirements.txt
```

---

## Implemented Work

### 1. Continued Pretraining

- Adapted pretrained LLMs to domain-specific corpora
- Dataset preprocessing and tokenization
- Causal language modeling
- Hugging Face Trainer pipeline

---

### 2. Instruction Fine-Tuning

- Fine-tuned TinyLlama using LoRA
- Mental health counseling conversation dataset
- Compared model responses before and after fine-tuning
- Generated responses using the adapted model

---

### 3. Financial Language Adaptation

- Fine-tuned Qwen2.5 on financial/news text
- Experimented with parameter-efficient fine-tuning
- Evaluated the same pipeline on a different domain

---

## Models

- TinyLlama
- Qwen2.5

---

## Datasets

- Mental Health Counseling Conversations
- Financial News Dataset
- TinyStories
- FineWeb
- Additional domain-specific corpora

---

## Technologies

- Python
- PyTorch
- Hugging Face Transformers
- PEFT
- LoRA
- TRL
- Accelerate
- BitsAndBytes
- Datasets
- Google Colab

---

## Workflow

```
Domain Dataset
        │
        ▼
Preprocessing
        │
        ▼
Tokenizer
        │
        ▼
Pretrained LLM
        │
        ▼
LoRA / PEFT Fine-Tuning
        │
        ▼
Inference
        │
        ▼
Comparison with Base Model
```

---

## Skills Demonstrated

- Large Language Model Fine-Tuning
- Instruction Tuning
- Continued Pretraining
- Parameter-Efficient Fine-Tuning (PEFT)
- LoRA
- Dataset Processing
- Hugging Face Ecosystem
- Model Inference

---

## Future Improvements

- Quantitative evaluation using benchmark datasets
- Hyperparameter optimization
- Model deployment using Hugging Face Spaces
- Experiment tracking with Weights & Biases

---

## Author

Personal learning project exploring practical techniques for adapting open-source Large Language Models to specialized domains.
