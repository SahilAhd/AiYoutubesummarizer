# 🎥 AI YouTube Summarizer

An AI-powered YouTube Video Summarizer built with **Streamlit**, **Agno**, and **Groq**. The application analyzes YouTube videos and generates structured summaries, making it easier to understand key concepts without watching the entire video.

---

## 🚀 Features

- 📺 Analyze any public YouTube video using its URL.
- 📝 Generate a detailed AI-powered summary.
- ⏱️ Create timestamp-based content breakdowns.
- 🎯 Highlight important topics and key takeaways.
- 📚 Organize video content into easy-to-read sections.
- ⚡ Fast responses powered by Groq LLMs.
- 🎨 Clean and interactive Streamlit interface.

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit**
- **Agno Framework**
- **Groq API**
- **YouTube Tools (Agno)**
- **YouTube Transcript API**
- **Python Dotenv**

---

## 📂 Project Structure

```text
Ytsummarizer/
│
├── ui.py                   # Streamlit user interface
├── youtube_analyzer.py     # AI Agent logic
├── requirements.txt        # Project dependencies
├── .gitignore
├── README.md
└── .env                    # API keys (not uploaded to GitHub)
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/AiYoutubesummarizer.git
```

Move into the project folder:

```bash
cd AiYoutubesummarizer
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the virtual environment.

### Windows

```bash
.venv\Scripts\activate
```

### Linux / macOS

```bash
source .venv/bin/activate
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root.

```env
GROQ_API_KEY=your_groq_api_key
```

---

## ▶️ Run the Application

```bash
streamlit run ui.py
```

The application will open in your browser at:

```
http://localhost:8501
```

---

## 📖 How It Works

1. Enter a YouTube video URL.
2. The Agno YouTube Tool retrieves the video transcript.
3. The Groq LLM analyzes the content.
4. The application generates:
   - Video Overview
   - Timestamp-wise Summary
   - Key Topics
   - Important Takeaways

---

## 📌 Future Improvements

- 🌍 Multi-language summarization
- 📄 Export summaries as PDF
- 🎤 Voice-based summaries
- 📑 Chapter-wise notes
- 🔍 Keyword extraction
- 💬 Chat with YouTube videos

---

**Sahil Ahmad**

Built using **Agno**, **Groq**, and **Streamlit** to simplify learning from YouTube videos through AI-powered summarization.
