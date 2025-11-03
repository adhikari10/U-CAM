🧠 U-CAM: Unified Cybersecurity AI Model
👥 Group — Tanya · Bibek · Chris · Dobrin
📘 About

U-CAM (Unified Cybersecurity AI Model) is a mini-project built using Gemini 2.0 Flash API and Gradio UI for real-time risk detection.
It demonstrates how AI and cybersecurity can be combined to analyze digital risks safely and effectively.

Functions:

Detects email phishing and transaction fraud

Returns structured JSON output containing risk level, analysis summary, and recommendations

Designed as a safe, demo-only app for educational purposes — no real data is used

The goal of U-CAM is to help students understand the integration of AI models like Gemini with cybersecurity use cases such as phishing and fraud detection.

⚙️ Key Features

🔁 Dual-Mode Input: The system allows users to choose between Transaction or Email analysis modes.

⚡ Real-Time AI Calls: Uses Gemini 2.0 Flash API with carefully designed instruct prompts to simulate risk analysis.

🧩 Structured Output: Gemini’s response is parsed into JSON format and displayed through Gradio using Markdown and Accordion components.

🔐 Input Validation: Regex and length validation are applied before API calls to ensure safe testing.

🧠 Educational Focus: Emphasizes the principles of prompt design, AI risk evaluation, and safe data handling.

🧰 Safety Measures

Output type: application/json (ensures no markdown execution or untrusted rendering).

Harm filters: Set to BLOCK_NONE during testing for controlled, educational visibility.

No real data: The app uses only mock or simulated inputs.

Input validation: Regex and field verification before sending any data to the API.

Safety disclaimer: All results are tagged with a disclaimer that this is a learning prototype, not a production security tool.

👩‍💻 Roles & Contributions
Member	Role	Main Tasks
Tanya	Team Lead	Designed Gradio UI, handled testing, managed presentation
Bibek	Backend Logic	Developed Gemini prompt logic, API integration, safety configuration
Chris	Email Logic	Created email phishing detection flow, wrote documentation
Dobrin	Output Clarity	Improved JSON readability, assisted with testing, and supported backup demo idea
🚀 How to Run

Open the notebook U-CAM_Final_Notebook.ipynb in Google Colab.

Set your Gemini API key in the notebook before running:

GOOGLE_API_KEY = userdata.get('ml_project')


Run all cells sequentially to start the Gradio interface.

Choose an input type (Transaction or Email), provide mock data, and click Submit to view the AI’s analysis.

⚠️ API Access Notes

The Gemini API key functioned only under Bibek’s personal Gmail account due to access restrictions.

University or shared accounts could not authenticate Gemini API usage.

As a workaround, the team included screenshots and demo videos of live output for the final presentation.

Additional safety checks and fallback messages were implemented to ensure that the app remains mock-only and non-destructive.

🧩 Tech Stack
Tool	Purpose
Python + Gradio	Front-end UI for user input and output display
Gemini 2.0 Flash API	AI model for phishing and fraud risk detection
Regex / JSON	Input validation and structured output formatting
Google Colab	Development and testing environment

🏁 Summary

U-CAM showcases how Generative AI models can be used responsibly in cybersecurity research and education.
It offers a hands-on way to explore AI-driven threat detection, data validation, and explainable outputs — all within a safe, mock-based environment.

This project represents the collaborative effort of Group 4 in combining cybersecurity awareness with AI innovation.

🧾 License

This repository is for educational purposes only.
All rights reserved © 2025 — Group 4, Metropolia University of Applied Sciences
