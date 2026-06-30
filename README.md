# Chinese-to-English-PowerPoint-Translator
A Streamlit-based web application that automatically translates Chinese PowerPoint (.pptx) presentations into English while preserving the original slide structure and formatting.
Chinese to English PowerPoint Translator

📌 Overview

This project is a Streamlit-based PowerPoint Translator that automatically translates Chinese (.pptx) presentations into English. It extracts text from each slide, translates it using the Google Translate API (googletrans), and generates a new PowerPoint presentation while preserving the original layout and formatting.

This tool is ideal for students, researchers, professionals, and educators who need to convert Chinese presentations into English quickly and efficiently.

⸻

🚀 Features

* Translate Chinese PowerPoint presentations into English
* Upload .pptx files directly through a web interface
* Preserve slide layout and formatting
* Automatic text extraction and translation
* Download the translated presentation instantly
* Interactive progress bar during translation
* Simple and user-friendly Streamlit interface

⸻

🛠 Technologies Used

* Python
* Streamlit
* python-pptx
* Google Translate (googletrans)
* BytesIO
* Time

⸻

📂 How It Works

1. Upload a Chinese PowerPoint (.pptx) file.
2. The application reads each slide.
3. Text from every text box is extracted.
4. The Google Translate API translates the text from Chinese to English.
5. The translated text replaces the original content.
6. A new PowerPoint file is generated for download.
Application Workflow

1. Launch the Streamlit application.
2. Upload a Chinese .pptx file.
3. Wait while the translation progress is displayed.
4. Download the translated English PowerPoint presentation.
