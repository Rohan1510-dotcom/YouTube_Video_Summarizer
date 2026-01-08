🎥 YouTube Transcript Summarizer

An NLP-based web application that extracts transcripts from YouTube videos and generates concise, human-readable summaries using a Transformer-based deep learning model. The application is built with Hugging Face Transformers, PyTorch, and Gradio.

📌 Project Overview

YouTube videos often contain long and information-dense content. This project automates the process of:

Extracting video transcripts

Handling long text limitations of transformer models

Generating abstractive summaries

Presenting results via a simple web interface

The system is designed to be lightweight, portable, and easy to deploy on local machines.

🧠 Key Features

🔗 Accepts any public YouTube video URL

📝 Automatically extracts video transcripts

🧩 Handles long transcripts using intelligent text chunking

🤖 Uses DistilBART (CNN-based) for abstractive summarization

⚠️ Limitations

Works only for public videos with captions enabled

Private videos and videos without subtitles are not supported

Extremely long videos may take longer to process
🌐 Interactive web UI using Gradio

💻 Runs on CPU or GPU (auto-detected)

📚 Learning Outcomes

Practical understanding of transformer token limits

Experience with abstractive text summarization

Hands-on use of Hugging Face pipelines

End-to-end ML application deployment

UI integration for ML models
