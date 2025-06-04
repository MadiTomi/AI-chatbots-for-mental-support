# 🧠 AI-Based Mental Health Support Chatbot

A diploma project developed by students of Astana IT University aimed at providing empathetic, AI-powered support for individuals facing mental health challenges. This chatbot uses a Retrieval-Augmented Generation (RAG) approach and integrates multiple language models to offer contextually appropriate and multilingual mental health conversations.

## 📌 Project Overview

This AI chatbot is designed to simulate mental health counseling sessions in a safe, supportive environment. Built using cutting-edge language models and real-world datasets, the chatbot:

- Recognizes user emotional states
- Provides non-judgmental, empathetic replies
- Supports English, Russian, and Kazakh languages
- Uses a combination of generative models via a RAG system

> ⚠️ Disclaimer: This tool is for educational and research purposes only. It is not a replacement for professional medical or psychological help.

---

## 🔍 Features

- 🌐 Multilingual support: English, Russian, and Kazakh
- 🤖 Hybrid AI integration: GPT-4-turbo, DeepSeek, Gemini 2.0 Flash
- 📚 RAG system with mental health conversation datasets
- 💬 Gradio interface for easy interaction and sharing
- 📁 Local testing in Google Colab with dataset preprocessing

---

## 🧰 Tech Stack

- **Programming Language**: Python
- **AI Models**:
  - GPT-4-turbo (OpenAI)
  - DeepSeek (Hugging Face)
  - Gemini 2.0 Flash (Google)
- **Frameworks**:
  - Gradio (Chat UI)
  - Transformers (Hugging Face)
- **Development Tools**: Google Colab, Jupyter Notebooks
- **Data Handling**: Pandas, PyArrow

---

## 📂 Datasets Used

1. **[Human and LLM Mental Health Conversations (Kaggle)](https://www.kaggle.com/datasets/birdy654/human-and-llm-mental-health-conversations)**  
   *Format*: CSV — English conversations between humans and LLMs.

2. **[Mental Health Chatbot Dataset (Hugging Face)](https://huggingface.co/datasets/heliosbrahma/mental_health_chatbot_dataset)**  
   *Format*: Parquet — Emotion-based English mental health dialogues.

3. **[Mental Health Counseling Conversations in Kazakh (Hugging Face)](https://huggingface.co/datasets/Eraly-ml/mental_health_counseling_conversations-kk)**  
   *Format*: CSV — Real-world Kazakh language counseling sessions.

---

## 🧠 How It Works

* The chatbot receives the user query.
* The RAG system retrieves relevant dialogue examples.
* The retrieved context is passed to one of the integrated models.
* A response is generated and displayed via Gradio.


## 👥 Authors

* **Tomiris Madiyarova** — GPT-4-turbo Integration, Model Deployment
* **Zhuldyz Salimgerey** — DeepSeek-7B-LLM Integration, Model Deployment
* **Gulzina Daulet** — Gemini 2.0 Flash Integration, Model Deployment

**Supervisor**: *Adaliyev Nurlan*
Department of Computational and Data Sciences
Astana IT University



## Acknowledgements

* OpenAI, Google, and Hugging Face teams for API and models
* Dataset contributors on Kaggle and Hugging Face
* Mental health professionals and volunteers for inspiration

