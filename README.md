# 🦜 LangChain: Summarize Text From YT or Website

This is a Streamlit web application that summarizes content from YouTube videos and websites using LangChain, Hugging Face models, and Groq API.

## 🚀 Features

- Summarize text from **YouTube videos** or **websites**.
- Uses **Mistral-7B-Instruct-v0.3** from Hugging Face for text summarization.
- Implements **LangChain's summarization chain** for efficient processing.
- Validates input URLs and API tokens for security.
- User-friendly **Streamlit UI** with error handling.

## How to Run
Run the Streamlit app using:
streamlit run app.py

## 🏗️ Tech Stack
- Python.
- Streamlit 🎨 (for UI)
- LangChain 🔗 (for LLM orchestration)
- Hugging Face Mistral-7B-Instruct 🤗 (for text generation)
- YouTubeLoader 📹 (for extracting transcripts)
- UnstructuredURLLoader 🌐 (for website scraping)
