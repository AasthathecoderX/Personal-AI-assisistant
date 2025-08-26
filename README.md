# 🤖 Lightweight Text-to-Text Chatbot Using Hugging Face Transformers

This project is a simple conversational chatbot built with Hugging Face Transformers and PyTorch.  
It leverages the FLAN-T5-small model (google/flan-t5-small) to generate natural language responses in a continuous interactive session.

## 🚀 Key Features

- Entirely Python-based, utilizes the Hugging Face transformers pipeline.
- Maintains a limited chat history to provide context (last 5 interactions).
- Interactive REPL-style loop (`while True`) for seamless chatting.
- Compact and efficient model (FLAN-T5-small) optimized for fast CPU/Colab execution.

## 📦 Installation

Install required Python packages:
```bash
!pip install transformers torch accelerate -q
