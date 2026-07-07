# 🩺 Medical AI Assistant

An AI-powered healthcare assistant that leverages **Google Gemini 3 Flash** to analyze medical images and provide AI-generated insights for educational purposes. Users can upload medical images such as **X-rays, CT scans, MRI scans, or skin images**, and receive structured observations, possible clinical considerations, and recommended next steps.

> **Disclaimer:** This application is intended for educational and informational purposes only. It does **not** provide medical diagnoses or replace professional medical advice.

---

## 🚀 Features

- 📷 Upload medical images (PNG, JPG, JPEG)
- 🤖 AI-powered image analysis using Google Gemini
- 🩺 Structured medical observations and findings
- 💡 Possible clinical considerations
- 📋 Recommended next steps
- ⚡ Fast and responsive Streamlit interface
- 🔒 Secure API key management with `.env`

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming | Python |
| AI | Google Gemini 3 Flash |
| Framework | Streamlit |
| Image Processing | Pillow (PIL) |
| Environment | python-dotenv |
| Version Control | Git & GitHub |

---

## 📂 Project Structure

```text
Medical-AI-Assistant/
│
├── app.py                 # Main Streamlit application
├── .env                   # Gemini API Key (not committed)
├── requirements.txt
├── README.md
└── assets/
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/ozandx/medical-ai-assistant.git

cd medical-ai-assistant
```

---

### 2. Create a virtual environment

Windows

```bash
python -m venv venv

venv\Scripts\activate
```

Mac/Linux

```bash
python3 -m venv venv

source venv/bin/activate
```

---

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Create a `.env` file

```env
GEMINI_API_KEY=YOUR_GEMINI_API_KEY
```

Get your API key from:

https://aistudio.google.com/app/apikey

---

### 5. Run the application

```bash
streamlit run app.py
```

---

## 📸 How It Works

1. Upload a medical image.
2. Click **Generate Analysis**.
3. The application sends the image to **Google Gemini**.
4. Gemini analyzes the image using a medical-focused prompt.
5. The AI returns:
   - Image Summary
   - Key Observations
   - Possible Clinical Considerations
   - Recommendations
   - Medical Disclaimer

---

## 📷 Supported Images

- Chest X-ray
- Brain MRI
- CT Scan
- Skin Lesion
- Dental X-ray
- Other medical images (PNG/JPG/JPEG)

---

## 🧠 AI Workflow

```text
User
   │
   ▼
Upload Medical Image
   │
   ▼
Streamlit Application
   │
   ▼
Google Gemini API
   │
   ▼
Medical Image Analysis
   │
   ▼
Structured AI Response
```

---

## 🔒 Security

- API keys are stored securely using `.env`.
- No uploaded images are permanently stored.
- All analyses are generated on demand.

---

## ⚠️ Disclaimer

This application uses Google's Gemini model to generate AI-assisted medical image analysis. The responses are intended **solely for educational and informational purposes** and should **not** be considered medical advice, diagnosis, or treatment. Always consult a qualified healthcare professional for medical evaluation and decision-making.

---

## 👨‍💻 Author

**Fauzan Dharmawan**

AI • Machine Learning • Data Engineering • Cloud Engineering#
