# NOTIVIO: AI-Powered Lecture and Meeting Summarization System
AI-powered system for lecture and meeting summarization
# OVERVIEW
Notivio is an AI-powered system that automatically converts lecture and meeting audio or documents into structured summaries. It uses Whisper for speech-to-text and GPT-4o-mini for LLM-based summarization, providing concise and organized outputs for students and professionals.
The system supports both audio input and document input, making it a full-stack AI application with a web interface.
# FEATURES
Speech-to-text transcription using Whisper
Audio Pre-processing
Document Extraction
Text Pre-processing
Summarization
Translation
Generate Flashcards
PDF Export
JSON storage for results
# Tech Stack
Frontend: HTML, CSS
Backend: Flask (Python)
AI Models: Whisper, GPT-4o-mini
File Processing: PyPDF2, python-docx, pptx libraries
Others: JSON, PDF generation tools
# System Architecture
User uploads audio or document
Audio → Whisper transcription
Text → Extraction 
System generates:
  Transcription
  Structured summary
  Flashcards
Exportable PDF

# How to Run
