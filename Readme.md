# 🦜 Summify-AI: YT & Web Content Summarizer

An elegant, lightweight AI-powered web application that extracts text from YouTube videos (transcripts) or standard web URLs and generates a concise, 300-word summary. Built using **Streamlit**, **LangChain**, and powered by high-speed inference via **Groq Cloud (Gemma-7b-It)**.

---

## 🚀 Features

*   **YouTube Transcript Extraction:** Automatically grabs video transcripts to summarize video content without needing to watch it.
*   **Web Scraping & Extraction:** Parses raw text from blog posts, documentation, or news articles while safely bypassing basic scraper blocks using custom headers.
*   **Lightning-Fast Inference:** Utilizes Groq API endpoints for near-instant summary generation.
*   **Clean UI:** Simple, interactive user interface built entirely in Python with Streamlit.

---

## 🛠️ Tech Stack

*   **Frontend/App Framework:** [Streamlit](https://streamlit.io/)
*   **LLM Orchestration:** [LangChain](https://www.langchain.com/)
*   **Inference Engine:** [Groq Cloud API](https://groq.com/)
*   **Model:** `Gemma-7b-It`
*   **Document Loaders:** `YoutubeLoader` & `UnstructuredURLLoader`

---
