
### Week 1: Environment Setup & Basic Processing

Goal: Establish the foundational development environment and implement basic educational content processing (PDF text extraction).

Overview :

This week focused on setting up the initial workflow in Google Colab. The primary objective was to ensure we can successfully ingest structured input materials (PDFs) and extract raw text from them, which will serve as the foundational data for our AI content generation agent in the upcoming weeks.

### Actions Completed

 1. Environment Setup

    * Initialized the development environment using Google Colab.

    * Installed necessary Python libraries for document processing and LLM integration: PyPDF2 (for reading PDFs) and langchain (for future AI agent orchestration).
     
    <img width="1429" height="632" alt="Screenshot 2026-02-24 231407" src="https://github.com/user-attachments/assets/fdfc7b39-76de-4f1f-8c81-66236de21390" />

    
    <img width="1142" height="84" alt="Screenshot 2026-02-24 231435" src="https://github.com/user-attachments/assets/33b0c696-73c1-4996-b095-69cf4b9d2eb5" />

 2. Document Upload Implementation

    * Utilized the google.colab library to create an interactive file upload widget.

    * This allows users to dynamically upload educational PDF materials directly into the Colab environment during runtime.

 3. Text Extraction Pipeline

    * Wrote a Python script utilizing PyPDF2 to process the uploaded document.

    * The script successfully identifies the uploaded file, reads the specific pages (currently targeting the first page for testing), and extracts the raw text.

    * This ensures the AI agent will have clean, readable text to process moving forward.

  <img width="1417" height="528" alt="Screenshot 2026-02-24 231453" src="https://github.com/user-attachments/assets/02ef66f6-c296-4bd1-9419-a8c3e4b22b22" />

  ### Output
  
  <img width="1383" height="376" alt="Screenshot 2026-02-24 231504" src="https://github.com/user-attachments/assets/4f162b38-bde1-4836-9712-b245067eb066" />


  ### Process Flow Diagram

```text
[Start: Google Colab Environment]
       │
       ▼
[Install Dependencies] ──────> (PyPDF2, LangChain)
       │
       ▼
[Ingest Data] ───────────────> (Upload PDF via Colab Widget)
       │
       ▼
[Process Document] ──────────> (Initialize PyPDF2 Reader)
       │
       ▼
[Extract Content] ───────────> (Target specific pages & pull text)
       │
       ▼
[Output] ────────────────────> (Raw Extracted Text ready for AI Agent)
```
  

### 🎥 System Demonstration


https://github.com/user-attachments/assets/395ec355-8700-4027-9a85-d57658a0f5f6

> **Demo Overview:** Implementation of the core ingestion pipeline, showcasing seamless PDF upload and real-time text extraction in the Google Colab environment.
---
