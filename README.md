# Pixcribe

A simple Streamlit application that generates AI-powered captions for uploaded images using Google Gemini 1.5 Flash.

## Features

- Upload `.jpg`, `.jpeg`, or `.png` images
- Generates descriptive captions using the Gemini API
- Clean and interactive Streamlit user interface

## Tech Stack

- Language: Python
- Framework: Streamlit
- AI Model: Google Gemini 1.5 Flash
- Image Processing: Pillow
- API Library: google-generativeai

## Requirements

- Python 3.7+
- Google Gemini API key
- Dependencies: `streamlit`, `Pillow`, `google-generativeai`

## Installation & Usage

1. **Install dependencies**

```
pip install streamlit Pillow google-generativeai
```

2. **Add your Google Gemini API key inside `app.py`**

Replace:

```
genai.configure(api_key="your-api-key-here")
```

3. **Run the application**

```
streamlit run app.py
```
