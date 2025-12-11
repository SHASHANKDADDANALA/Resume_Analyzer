AI Resume Analyzer

An LLM-powered resume evaluation system built with Streamlit, OpenAI, and PyPDF2 that performs structured critique, identifies improvement areas, and generates role-specific feedback in real time.

Developed By
Shashank

Architecture Overview

User uploads a resume (PDF / TXT)
Text is extracted using PyPDF2 or UTF-8 decoding
Application builds a role-aligned prompt dynamically
OpenAI GPT model performs structured analysis
Output is rendered with section-wise recommendations
Errors, empty input, and oversized text are gracefully handled

Tech Stack

Python
Streamlit
OpenAI Chat Completions (gpt-4o-mini)
PyPDF2 (PDF text extraction)
dotenv (secure API key management)

How to Run
To run the AI Resume Analyzer locally, first create and activate a Python virtual environment, then install all dependencies listed in requiremrnts.txt. Add your OpenAI API key inside a .env file in the project root. Once the environment is set up, start the Streamlit application by running `streamlit run main.py`. This will launch a local web interface where you can upload a PDF or text resume and receive an AI-generated, role-specific critique.
