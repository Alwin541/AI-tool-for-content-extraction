# AI-tool-for-content-extraction and saving
Langchain chatbot to summarize content in a file
This project implements an AI-powered chatbot that can fetch research papers from the web, extract their content, generate a summary using Gemini 1.5 API, and finally save the results into a Word document.

📌 Project Overview

The chatbot can:

🔎 Fetch research papers online (from URLs or APIs)

📑 Extract and process text from research articles

🧠 Summarize the content using Gemini 1.5 via LangChain

💬 Provide conversational interaction for clarifications

📄 Save the summarized output into a Word (.docx) file

This is especially useful for students, researchers, and professionals who want quick insights from lengthy academic papers.

⚙️ Tech Stack

Language: Python

Frameworks/Libraries:

LangChain
 – LLM orchestration

Google Gemini 1.5 API
 – LLM model

requests / beautifulsoup4 – For fetching papers

python-docx – For generating Word files

Model: Gemini 1.5 (Google)

🧑‍💻 Implementation Steps

Fetch Research Paper

Provide a URL or query.

Script downloads or scrapes the research content.

Content Extraction

Clean and parse text.

Split into manageable chunks (LangChain text splitters).

Summarization

Use Gemini 1.5 to generate section-wise or overall summary.

Save to Word

Export the summarized content into a .docx file for offline use.

Interactive Chatbot

User can ask follow-up questions about the paper.
