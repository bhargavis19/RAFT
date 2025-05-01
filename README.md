# RAFT

This project implements a **local alternative** to the RAFT (Retrieval-Augmented Fine-Tuning) framework for training domain-adapted generative language models. Originally, RAFT relies on **Azure Foundry** for synthetic data generation and fine-tuning — a service we did not have access to due to subscription limitations.

To work around this, we built a pipeline that performs **end-to-end fine-tuning locally** using open-source tools like Hugging Face Transformers and PyTorch. We used models such as **T5**, **BART**, and **FLAN-T5**, and evaluated their performance using standard metrics (ROUGE, BLEU, METEOR).

---

## 🧪 Models Used

We fine-tuned and evaluated the following models:
- [`t5-base`](https://huggingface.co/t5-base)
- [`facebook/bart-base`](https://huggingface.co/facebook/bart-base)
- [`google/flan-t5-base`](https://huggingface.co/google/flan-t5-base)

---
