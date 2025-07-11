# Voicemail Urgency Detection

This is a work-in-progress project for detecting urgency levels in voicemail transcriptions using Google Vertex AI. The goal is to build a backend service that classifies voicemails as **urgent** or **non-urgent**, helping streamline response prioritization in IT support.

---

## 🚀 What is this?

- Analyze voicemail transcriptions using machine learning to detect urgency.
- Fine-tune a machine learning model with Google Vertex AI for more acurate detection.
- When the urgent voicemail is detected, the system send text via Twilio to notify.

---

## 🧠 Why I am building this?

This project was inspired by the need to triage customer voicemails quickly and efficiently in IT service environments especially **after work hours**.

---

## ✅ Current Status

- [x] Initial research
- [x] Google NLP tried (results not useful)
- [x] Decided to fine tune the machine learning model on Vertex AI
- [x] Dataset preparation with real-world voicemail samples. Manually labeling for all voicemai records.
- [x] Model fine-tuning 
- [x] Deployment
- [ ] Add database to store the voicemail data

---

## 📂 Tech Stack

- Python
- Flask
- Google Cloud Vertex AI
- Google Cloud NLP (initially)
- Google Cloud Run
- Docker

---

## 📝 Future Improvements

- Use more advanced NLP (e.g., transformers like BERT).
- Improve dataset with more sample data.

---


## 📌 Note

This project is **not complete yet**. It is being built step by step to improve my skills in backend development, cloud services, and applied AI.
