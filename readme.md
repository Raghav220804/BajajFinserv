# Lab Report OCR Extractor API

This FastAPI service accepts PNG lab report images and extracts:
- Test names
- Test values
- Reference ranges
- Whether the value is out of range

## Run Locally

```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
uvicorn main:app --reload
http://127.0.0.1:8000/docs #for fastapi 


