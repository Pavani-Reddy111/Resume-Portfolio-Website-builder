# 🌐 AI Resume, Portfolio & Website Builder

## 📌 Overview
AI Resume, Portfolio & Website Builder is a **Streamlit-based AI application** that generates **professional resumes, portfolio content, and complete website text** based on user prompts.

Using **LangChain** and an LLM, the application converts user requirements into **structured, ready-to-use content** for resumes, portfolios, and custom websites.

---

## 🎯 Key Features
- AI-powered resume generation
- Portfolio content creation
- Website content generation based on user prompts
- Custom sections (About, Skills, Projects, Experience, Contact)
- Clean and interactive Streamlit UI
- Reusable, professional outputs

---

## 🧠 How It Works
1. User provides requirements or prompts
2. AI understands the intent (resume / portfolio / website)
3. Structured content is generated accordingly
4. Output can be reused for resumes, portfolios, or websites
5. Content is suitable for personal, academic, or professional use

---

## 🏗️ Tech Stack
- **Frontend:** Streamlit  
- **AI Framework:** LangChain  
- **LLM:** Google Gemini / OpenAI (configurable)  
- **Language:** Python  

---

## 📁 Project Structure
```
resume-portfolio-website-builder/
├── app.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Setup & Run Locally
```bash
pip install -r requirements.txt
streamlit run app.py
```

Create a `.env` file:
```
GOOGLE_API_KEY=your_api_key_here
```

---

## ☁️ Deploy on Streamlit Cloud
1. Push code to GitHub
2. Create a Streamlit Cloud app
3. Select `app.py` as the main file
4. Add secret:
```
GOOGLE_API_KEY = "your_api_key_here"
```

---

## 🎓 Learning Outcomes
- AI-driven resume, portfolio, and website generation
- Prompt engineering for structured web content
- Streamlit-based interactive applications
- LangChain integration for real-world use cases

---

## 👩‍💻 Author
**Pavani Reddy**
