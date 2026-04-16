# 🚀 Converto

Your files. Your rules.

A local-first all-in-one file converter built with Flask.

## 🔥 Features
- PDF → DOCX  
- DOCX → PDF  
- PPT → PDF  
- PDF → PPT  
- Merge PDFs  
- YouTube / Instagram → MP3  

## ⚡ Run locally

```bash
git clone https://github.com/chefken/converto.git
cd converto
python3 -m venv venv
source venv/bin/activate
pip install flask pdf2docx python-docx PyMuPDF yt-dlp python-pptx Pillow
python3 app.py