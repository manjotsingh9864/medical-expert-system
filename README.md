# 🩺 Medical Expert System – AI-Powered Diagnosis  
**A rule-based AI Expert System for predicting Malaria & Typhoid using Forward Chaining.**  
Built by **Manjot Singh** (AI & Data Science)

🔗 **Live Demo:** https://manjot-expert-system.netlify.app  
📂 **GitHub Repo:** (Add your repo link here)

---

## 🚀 Project Overview
This project is a fully functional **AI-based Medical Expert System** designed to help with early diagnosis of **Malaria and Typhoid** using symptom-based inference.

It uses:

- ✔ Forward Chaining  
- ✔ Rule-Based Knowledge System  
- ✔ Confidence scoring  
- ✔ Dynamic symptom selection  
- ✔ Stunning React + Tailwind UI  

This system analyzes user-selected symptoms, matches them with disease rules, and generates a medically meaningful prediction with recommendations.

---

# 🧠 How It Works (Algorithm)
This system is built on a **Rule-Based Expert System** using **Forward Chaining**.

### 🔍 Steps:
1. User selects symptoms  
2. System checks symptoms against predefined rules  
3. Required symptoms → must match  
4. Optional symptoms → increase confidence  
5. The disease with the highest score is predicted  

### 🧼 Formula:
Required Score  = (Matched Required Symptoms / Total Required) * 100
Optional Score  = (Matched Optional Symptoms / Total Optional) * 50
Total Score     = Required Score + Optional Score
### 📌 Diseases Implemented:
- **Malaria**
- **Typhoid**

Matches perfectly with the Rule Table provided in practical manual.

---

# ✨ Features
### 🌡 Symptom-Based Diagnosis  
Interactive symptom selection (10+ symptoms)

### 🤖 AI Inference Engine  
- Rule Matching  
- Confidence Calculation  
- Forward Chaining  
- Required/Optional Symptom Logic  

### 🎨 Professional UI  
- React 18  
- Tailwind CSS  
- Glassmorphism  
- Animations  
- Beautiful Icons  

### 📊 Results Dashboard  
- Disease name  
- Confidence percentage  
- Required/Optional symptoms matched  
- Recommendations  
- Patient summary  

### 📱 Fully Responsive  
Works on all devices.

---

# 🛠 Tech Stack
| Technology | Purpose |
|-----------|----------|
| **React 18** | Main UI & Component Handling |
| **Tailwind CSS** | Styling & Layout |
| **Babel (JSX)** | In-browser JSX support |
| **Netlify** | Deployment |
| **Rule-Based AI Logic** | Diagnosis Engine |

---

# 📷 Screenshots  
(Add images after uploading them in repo)

---

# 📦 Installation Guide (Local Run)

### 1️⃣ Clone the repo  
```bash
git clone <https://github.com/manjotsingh9864/medical-expert-system>
2️⃣ Open project folder
cd expert
3️⃣ Run locally: Either use Live Server OR
python3 -m http.server 8000
Visit: http://localhost:8000
🌍 Deployment

The project is deployed on Netlify:
👉 https://manjot-expert-system.netlify.app

To redeploy, drag the folder into:
https://app.netlify.com/drop
OR connect repo for automatic deployment.

⸻

🔮 Future Enhancements
	•	Add more diseases
	•	Add probability-based ML model
	•	Add chat-based diagnosis
	•	Add database for patient history
	•	Add user authentication
	•	Add API integration

⸻

👨‍💻 Author – Manjot Singh

🎓 B.Tech CSE (Data Science & AI)
📍 India

📧 Email: singhtmanjot@gmail.com
📞 Phone: 7087736640
🔗 LinkedIn: https://linkedin.com/in/manjot-singh-ds

⸻

⭐ Support This Project

If you liked this project, consider giving it a ⭐ on GitHub!
Your support motivates me to build more awesome AI projects.