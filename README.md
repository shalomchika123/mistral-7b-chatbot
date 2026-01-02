# 🤖 Mistral-7B Chatbot

A specialized conversational AI interface built with **Mistral-7B-Instruct-v0.2**. This project demonstrates efficient LLM inference on consumer hardware using 4-bit quantization.

## 🚀 Key Features
* **Memory:** Retains context for up to 6 turns of conversation.
* **Safety Layer:** Custom keyword filtering to prevent unsafe outputs.
* **Efficient Inference:** Uses `bitsandbytes` (NF4 quantization) to run a 7B model on a free T4 GPU (kaggle notebook).
* **Full-Stack UI:** Integrated **Gradio** interface with latency and token metrics.

## 🛠️ Tech Stack
* **Model:** Mistral-7B-Instruct-v0.2
* **Libraries:** Hugging Face Transformers, PyTorch, Gradio
* **Optimization:** 4-bit Quantization (NF4) via bitsandbytes.

## 📊 Evaluation
Includes a built-in automated test suite to verify:
* Factuality
* Safety Guardrails
* Hallucination Resistance
