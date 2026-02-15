# Questify - AI Question Paper Generator

Questify is an AI-powered tool that helps educators generate professional question papers from PDF study materials in seconds. It uses Bloom's Taxonomy to ensure a balanced mix of cognitive levels.

## Features
- **AI-Powered Generation**: Extracts text from PDFs and generates questions using OpenRouter/LLMs.
- **Bloom's Taxonomy**: Supports L1 (Remember), L2 (Apply), and L3 (Create) levels.
- **Export Options**: Download papers in PDF and Word (.docx) formats.
- **Google Login**: Secure authentication using Google OAuth.
- **History**: Save and manage previously generated papers.

## Setup
1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.env` file with your API keys (OpenRouter, Google OAuth, Secret Key).
4. Run the app:
   ```bash
   python app.py
   ```

## Tech Stack
- Python (Flask), Tailwind CSS, SQLite, OpenRouter API