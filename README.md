# TTS-STT-Chatbot
# 🗣️ Hotel Management Chatbot (RAG with Voice Input/Output)



This repository contains an interactive Streamlit chatbot powered by Google's Gemini-1.5-Flash model, designed to provide information about MaitriAI's services. It leverages Retrieval Augmented Generation (RAG) to answer questions based on a provided document (`MaitriDoc.pdf`) and features both text-based and voice-enabled interaction (Speech-to-Text and Text-to-Speech).
### Demo: 
https://youtu.be/6NEOp8Du240?si=bgduObL-vjq9a3i5
## ✨ Features

*   **Intelligent Q&A:** Answers questions about MaitriAI's services using a RAG architecture with `MaitriDoc.pdf` as the knowledge base.
*   **Conversational History:** Maintains chat history to provide context-aware responses.
*   **Speech-to-Text Input:** Allows users to interact with the chatbot using their voice, transcribing speech to text.
*   **Text-to-Speech Output:** Converts chatbot responses into spoken audio for an intuitive conversational experience.
*   **Streamlit UI:** User-friendly web interface for seamless interaction.
*   **Google Gemini-1.5-Flash:** Powered by a cutting-edge LLM for accurate and relevant responses.
*   **Custom Persona:** "Alex," an AI assistant specializing in MaitriAI's offerings.
*   **Contextual Guardrails:** Designed to answer only MaitriAI-related queries, gracefully handling out-of-scope questions.

## 🛠️ Technologies & Tools

*   **Python:** Primary programming language.
*   **Streamlit:** For building the interactive web application.
*   **LangChain:** For orchestrating the RAG pipeline.
*   **Google Gemini-1.5-Flash:** Large Language Model.
*   **GoogleGenerativeAIEmbeddings:** For creating document embeddings.
*   **Chroma DB:** Vector store for semantic search and retrieval.
*   **PyPDFLoader:** For loading and parsing PDF documents.
*   **RecursiveCharacterTextSplitter:** For efficient document chunking.
*   **pyttsx3:** Python text-to-speech library.
*   **SpeechRecognition:** Python library for speech recognition (using Google Web Speech API).
*   **python-dotenv:** For managing environment variables.
*   **requests & streamlit-lottie:** For integrating Lottie animations.

## 🚀 Getting Started

Follow these instructions to set up and run the MaitriAI Chatbot locally.

### Prerequisites

*   Python 3.8+
*   `pip` (Python package installer)
*   A Google API Key with access to Gemini models.

### 1. Clone the Repository

```bash
git clone https://github.com/Aryakumarjaiswal/TTS-STT-Chatbot.git
```
### 2. Load API Key

```bash
GOOGLE_API_KEY="YOUR_GOOGLE_GEMINI_API_KEY"
```

### 3. Install Dependencies
```bash
python -m venv venv
source venv/bin/activate  # On Windows: `venv\Scripts\activate`
pip install -r requirements.txt
```
### 4.. Run the Application
```bash
streamlit run app.py
```

