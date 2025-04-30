# 🧠 Fine-Tuning Gemma 2B with LoRA for Quote Generation

This project demonstrates how to fine-tune Google's [Gemma-2B](https://ai.google.dev/gemma) large language model using [LoRA](https://arxiv.org/abs/2106.09685) (Low-Rank Adaptation) on a dataset of quotes and authors. The goal is to generate relevant author names based on quotes or create quote-author pairs.

## 🔧 Model & Techniques
- **Base Model**: [`gemma-2b`](https://huggingface.co/google/gemma-2b)
- **Adapter**: [LoRA via PEFT](https://github.com/huggingface/peft)
- **Hardware**: Google Colab with T4 or A100
- **Libraries**: `transformers`, `peft`, `datasets`, `bitsandbytes`
