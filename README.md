# 📝 Resume Editor with Mock AI Enhancement

A **web-based Resume Editor** that allows users to:
- Upload and edit resumes.
- Enhance sections with a mock AI backend.
- Save and retrieve resume data using FastAPI.
- Download the final resume as JSON.

---

## 🚀 Features

✅ **Frontend (React)**
- Upload (.pdf/.docx) files (mock parsing with dummy data).
- Editable fields (Name, Experience, Education, Skills).
- "Enhance with AI" button per section to send content to backend and display enhanced text.
- Save complete resume data to backend.
- Download resume as JSON.

✅ **Backend (FastAPI)**
- `POST /ai-enhance` - Mock AI enhancement of resume sections.
- `POST /save-resume` - Stores resume JSON on disk or in memory.
- Auto-generated Swagger Docs at `/docs`.

---

## 📂 Project Structure

