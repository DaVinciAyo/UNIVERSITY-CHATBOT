# UNIVERSITY-CHATBOT
CHATBOT
Here is a **short, clean README** suitable for **public GitHub**.

It keeps purpose, clarity, and credibility without academic length.

---

# Wrexham University RAG Chatbot

A retrieval-augmented chatbot that answers student questions using official Wrexham University documents.
Responses are generated from retrieved source text rather than model memory.

---

## What it does

* Answers questions on admissions, courses, fees, and regulations
* Retrieves relevant document sections using FAISS
* Generates grounded answers with a language model
* Avoids guessing when information is unavailable

---

## How it works

1. University documents are chunked and embedded
2. FAISS retrieves relevant content for each query
3. Retrieved text is injected into a grounded prompt
4. The model answers strictly from that context
5. Gradio provides a simple chat interface

---

## Tech stack

* Python
* Hugging Face Transformers
* LangChain
* FAISS
* Gradio

---

