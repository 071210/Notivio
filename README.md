# NOTIVIO: AI-Powered Lecture and Meeting Summarization System
Automatically transcribe and summarize lectures or meetings from audio files and documents using state-of-the-art AI models.
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
LayerTechnologySpeech-to-TextOpenAI Whisper (whisper-small)LLM SummarizationGPT-4o-mini (OpenAI API)BackendPython, FlaskDocument ParsingPyMuPDF, python-docx, python-pptxFrontendHTML, CSS, JavaScriptStorageJSON
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
