# Multi-Language-Translator
The Multi-language Course Content Translator Agent uses IBM Watsonx.ai and RAG to translate academic materials into regional languages while preserving technical accuracy. It supports PDFs, DOCs, PPTs, and ensures inclusive education by removing language barriers for students from diverse linguistic backgrounds.


Multi-language Course Content Translator Agent

Overview
The "Multi-language Course Content Translator Agent" is an AI-powered tool that enables automatic, context-aware translation of academic course materials into multiple regional languages. Built using "IBM Watsonx.ai", "IBM Granite or LLaMA-3 models", and "Retrieval-Augmented Generation (RAG)", it ensures translations are both linguistically accurate and technically sound.

Key Features
- Translate into multiple languages (Hindi, Tamil, Marathi, Bengali, Chinese, etc.)
- Upload course materials in `.pdf`, `.docx`, `.pptx`, or `.txt`
- Uses academic glossaries to preserve subject-specific terminology
- Powered by IBM Granite or LLaMA-3-70B on Watsonx.ai
- Returns downloadable translated files
- Promotes inclusive education and language equity

Architecture
1. Frontend : Simple UI for file upload and language selection (HTML/JS or Streamlit)
2. Backend : Python (Flask/FastAPI)
3. LLM Service : IBM Watsonx.ai with Granite/LLaMA-3
4. Storage : IBM Cloud Object Storage
5. Glossary/RAG: Static JSON or vector-based glossary lookup

How It Works
1. User uploads course content and selects a target language.
2. System extracts text and retrieves relevant glossary terms.
3. A RAG-enhanced prompt is sent to the foundation model.
4. Translated output is generated and returned for download.

Technologies Used
- IBM Cloud Lite (Watsonx.ai, Object Storage)
- IBM Granite / LLaMA-3-70B Instruct
- Retrieval-Augmented Generation (RAG)
- Python, Flask, HTML/JS
- Optional: ChromaDB / Weaviate for glossary storage

Use Cases
- Academic institutions supporting multilingual learners
- Translating technical lecture content for rural or regional audiences
- Converting national-level curriculum into native languages

Future Enhancements
- Voice-to-text and OCR integration
- AI chatbot for interactive explanations
- LMS integration for adaptive learning
- Auto-summarization of translated content

Authors
Developed as part of "IBM SkillsBuild for Academia"
