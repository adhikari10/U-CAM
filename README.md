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
---

## 🌐 Live Demo  

Try out the live version of **U-CAM** hosted on Hugging Face Spaces:  

👉 [**Launch Demo on Hugging Face**](https://huggingface.co/spaces/bibek2/U-CAM)

### 🖼️ Preview  

#### Transaction Mode  
![Transaction Mode](https://huggingface.co/spaces/bibek2/U-CAM/resolve/main/Demo/Transaction.png)

#### Analysis Output  
![Gemini Risk Analysis](https://huggingface.co/spaces/bibek2/U-CAM/resolve/main/Demo/Gemini_analysis.png)  

#### Email Mode  
![Email Mode](https://huggingface.co/spaces/bibek2/U-CAM/resolve/main/Demo/Email.png)  

#### Presentation
[View Full Presentation (Google Drive)] (https://drive.google.com/file/d/1dDZiPYCXNuL1jHE7oWdIDEfRW-v_O3mp/view?usp=sharing)

#### Team Reflection
- [4Ls Reflection Document (Google Drive)](https://drive.google.com/file/d/1NwHb3nnRp3DMvrtwLEn8B886QBqoVkbE/view?usp=sharing)

### 🧠 How It Works  

1. Choose between **Transaction** or **Email** input mode.  
2. Fill in the required mock data fields (e.g., transaction amount, location, or sender).  
3. Click **“Analyze with Gemini”**.  
4. The app calls **Gemini 2.0 Flash API** and returns a **JSON-based risk analysis** that is converted to Markdown in Gradio.  
5. The final section displays:  
   - **Risk level** (Low/Medium/High)  
   - **Reason & Indicators**  
   - **Recommendations**  
   - **Optional Cybersecurity Tips**  

---

