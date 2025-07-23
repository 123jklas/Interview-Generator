# Ready2Interview 🎤🤖

An AI-powered interview preparation assistant that analyzes your resume and generates personalized, company-specific interview questions using LLMs.

## 🔍 Features

- 📄 Resume parsing from uploaded PDF
- 🏢 Real-time company research using web search
- 🧠 Interview question generation with GPT-based LLM (OpenAI or local models like LLaMA3)
- 🗣️ Voice input/output using Whisper and TTS
- 🧪 Feedback on answers based on resume + emotion analysis (if available)

---

## 🛠️ Tech Stack

- Python, Streamlit
- LangChain, FAISS, Tavily Search
- LLaMA3 via Ollama (free local LLM)
- Whisper (speech-to-text), pydub (audio handling)

---

## Team & Credits

This project was originally initiated as a collaboration with Jihyung Park(https://github.com/jihyung803).  
This version reflects continued development and enhancements I implemented independently.

---

## 🚀 Quick Start

### 🔐 Using OpenAI GPT (paid)

1. Sign up at [OpenAI](https://platform.openai.com/)
2. Go to your [API Keys](https://platform.openai.com/account/api-keys)
3. Create a `.env` file in your project root:

```env
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxx

```bash
# install dependencies
pip install -r requirements.txt

# run app
streamlit run main.py
