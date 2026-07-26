Got it! ✅
You want the **entire README rewritten cleanly**, *removing the original repo link* and **replacing it with your new repository**:

👉 **`https://github.com/Shivaamm18/Leaf-Disease-Detection-.git`**

And you want a **clean, professional, simplified, and updated README** for your project.

Below is your **brand-new README**, fully rewritten, polished, and using **your GitHub repo link only**.
No reference to the old repo exists anywhere.

---

# 🌿 Leaf Disease Detection System

**AI-Powered Crop Health Analysis with FastAPI + Streamlit + Groq Llama Vision**

[![FastAPI](https://img.shields.io/badge/FastAPI-0.116.1-009688.svg?style=flat\&logo=fastapi)](https://fastapi.tiangolo.com/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.28+-FF4B4B.svg?style=flat\&logo=streamlit)](https://streamlit.io/)
[![Python](https://img.shields.io/badge/Python-3.8+-3776ab.svg?style=flat\&logo=python)](https://www.python.org/)
[![Groq](https://img.shields.io/badge/Groq-AI%20Powered-orange.svg?style=flat)](https://groq.com/)

An enterprise-ready AI system that identifies plant leaf diseases using **Meta Llama Vision models** through the **Groq API**.
This system provides:
✔ Accurate disease detection
✔ Severity estimation
✔ Confidence scoring
✔ Treatment recommendations

It includes a **FastAPI backend** and an **interactive Streamlit frontend** for seamless user experience.

---

# 🚀 Clone the Repository

```bash
git clone https://github.com/Shivaamm18/Leaf-Disease-Detection-.git
cd Leaf-Disease-Detection-
```

---

# 📁 Project Structure

```
Leaf-Disease-Detection-/
│── main.py                # Streamlit UI
│── app.py                 # FastAPI backend
│── utils.py               # Helper utilities
│── LeafDisease/
│     └── main.py          # Core AI detector engine
│── requirements.txt       # Dependencies
│── test_api.py            # API test cases
│── Media/                 # Test images
│── vercel.json            # Deployment config
│── .env.example           # Environment template
```

---

# 🎯 Key Features

### 🌱 AI Disease Detection

* Detects fungal, bacterial, viral, pest-related, nutrient deficiencies
* Works with JPG/PNG/WebP/TIFF
* Outputs disease name, severity, confidence %, symptoms, causes, and treatment steps

### ⚡ Fast Performance

* Powered by **Groq Llama Vision**
* Sub-5-second analysis
* Supports large image files (up to 10MB)

### 🧑‍💻 Dual Interface

* **Streamlit UI** → for end-users
* **FastAPI Backend** → for developers & integrations

### 📊 Database Support

* Stores history using SQLite
* Enables analytics dashboards

---

# 🔧 Installation Guide

## 1️⃣ Create Virtual Environment

### Windows:

```bash
python -m venv venv
.\venv\Scripts\activate
```

### Linux/macOS:

```bash
python -m venv venv
source venv/bin/activate
```

## 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

## 3️⃣ Setup Environment Variables

Create a `.env` file:

```
GROQ_API_KEY=your_groq_api_key_here
MODEL_NAME=meta-llama/llama-4-scout-17b-16e-instruct
DEFAULT_TEMPERATURE=0.3
DEFAULT_MAX_TOKENS=1024
```

---

# ▶️ Running the Application

## Option A — **Run Streamlit UI**

```bash
streamlit run main.py
```

Interface opens at:

👉 [http://localhost:8501](http://localhost:8501)

## Option B — **Run FastAPI Backend**

```bash
uvicorn app:app --reload --port 8000
```

API Docs:

👉 [http://localhost:8000/docs](http://localhost:8000/docs)
👉 [http://localhost:8000/redoc](http://localhost:8000/redoc)

## Option C — **Run Both**

Terminal 1:

```bash
uvicorn app:app --reload --port 8000
```

Terminal 2:

```bash
streamlit run main.py
```

---

# 📡 API Endpoints (FastAPI)

### **POST /disease-detection-file**

Upload an image → receive JSON report

Example response:

```json
{
  "disease_detected": true,
  "disease_name": "Leaf Spot",
  "severity": "moderate",
  "confidence": 88.5,
  "symptoms": ["Brown circular lesions", "Yellow halo"],
  "possible_causes": ["High humidity", "Fungal growth"],
  "treatment": ["Apply fungicide", "Improve air circulation"],
  "analysis_timestamp": "2025-01-10T12:30:45Z"
}
```

---

# 🧪 Testing

### Run API Tests:

```bash
python test_api.py
```

### Manual Testing:

Upload sample images from `/Media` folder.

---

# 🌐 Deployment

### ✅ Deploy to Vercel

```bash
vercel --prod
```

Set environment variable on Vercel:

* `GROQ_API_KEY`

### Other Supported Platforms:

* Streamlit Cloud
* Railway
* Docker
* Heroku

---

# 📝 License

This project is licensed under the **MIT License**.
You are free to use, modify, and distribute.

---

# 🌱 About the Project

This system empowers agriculture using AI by making plant disease diagnosis fast, accessible, and highly accurate.
Perfect for farmers, researchers, students, and agritech companies.

---

If you want:
✅ A **PDF Documentation**
✅ A **Full Project Report**
✅ A **LaTeX (let x) Report**
✅ A **Project PPT**
I can generate that too.
