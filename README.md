# Email-generator-project
Email Generator that creates professional emails from user inputs. Includes a lightweight template-based generator for fast structured emails and an AI-powered model (Hugging Face Transformers) for context-aware, tone-controlled email generation. Useful for job applications, follow-ups, meeting scheduling, and marketing copy
# Email Generator (AI + Google Colab)

This project is an **AI-powered Email Generator** that creates professional, context-aware emails based on your inputs.  
It uses the **Hugging Face Transformers** library with GPT-based models to generate emails in various tones (formal, friendly, persuasive).

---

## 🚀 Features
- Generates complete professional emails from:
  - Purpose of the email
  - Recipient name
  - Key points to include
  - Desired tone (formal/friendly/persuasive)
- Uses **Hugging Face pipelines** for fast inference
- Works in **Google Colab** or locally with Python
- Adjustable creativity via temperature/top-p sampling

---

## 📂 Files
- `ai_email_generator_colab.ipynb` → Google Colab notebook for AI-based generation
- `requirements.txt` → List of dependencies
- `samples/` → Folder containing example generated emails

---

## 🛠 Installation (Local)
```bash
pip install transformers torch

purpose = "following up on my M.Tech application"
recipient_name = "Dr. Sharma (Admissions Committee)"
key_points = [
    "I applied on 10th June",
    "I have research experience in VLSI and ML",
    "I am available for interview this week"
]
tone = "formal"
Subject: Follow-Up on M.Tech Application

Dear Dr. Sharma,

I hope this message finds you well. I am writing to follow up on my M.Tech application, submitted on 10th June. 
With my research background in VLSI and Machine Learning, I believe my skills align with the requirements of the program. 
I am available for an interview this week and would be happy to provide any additional information.

Sincerely,  
Adrija Vishwakarma
