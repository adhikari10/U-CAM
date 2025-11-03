# 🧠 U-CAM: Unified Cybersecurity AI Model  

### 👥 Group — Tanya · Bibek · Chris · Dobrin  

---

## 📘 About  
**U-CAM (Unified Cybersecurity AI Model)** is a mini-project built using **Gemini 2.0 Flash API** and **Gradio UI** for **real-time risk detection**.  
It demonstrates how **AI and cybersecurity** can be combined to analyze threats in a safe, educational setup.  

**Main Functions:**  
- Detects **email phishing** and **transaction fraud**  
- Returns **structured JSON output** with risk levels, explanations, and recommendations  
- Designed as a **demo-only project** — no real data used  

---

## ⚙️ Key Features  

- 🔁 **Dual-Mode Input:** Choose between *Email* or *Transaction*  
- ⚡ **Real-Time Gemini Calls:** Uses Gemini 2.0 Flash API with instruct prompting  
- 🧩 **Structured Output:** JSON displayed via Gradio using Markdown + Accordion layout  
- 🔐 **Validation:** Regex + input field checks before API calls  
- 🧠 **Educational Focus:** Demonstrates AI integration with cybersecurity  

---

## 🧰 Safety Measures  

- **Output Type:** `application/json` (no markdown execution)  
- **Harm Filters:** All set to `BLOCK_NONE` during demo for visibility  
- **Mock Data Only:** No personal or sensitive data used  
- **Validation:** Regex-based checks before API requests  
- **Disclaimers:** All outputs clearly state that results are for educational purposes only  

---

## 👩‍💻 Roles & Contributions  

| Member | Role | Key Tasks |
|:--|:--|:--|
| **Tanya** | Team Lead | Gradio UI, testing, presentation |
| **Bibek** | Backend Logic | Gemini prompts, API integration, safety setup |
| **Chris** | Email Logic | Phishing detection logic, documentation |
| **Dobrin** | Output Clarity | JSON formatting, testing, backup idea |

---

## 🚀 How to Run  

1. Open **`U-CAM_Final_Notebook.ipynb`** in **Google Colab**.  
2. Set your Gemini API key before running:  
   ```python
   GOOGLE_API_KEY = userdata.get('ml_project')
