<!-- ========================= -->
<!--          VEDYURA         -->
<!-- ========================= -->

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&weight=700&size=32&pause=1200&color=22C55E&center=true&vCenter=true&width=900&lines=Vedyura+%E2%80%94+AI-Powered+Ayurvedic+Diet+Management+Prototype;Doctor+%2B+Patient+Workflow;Personalized+Diet+Charts+%26+Health+Analysis;Built+for+Smart+Nutrition+Recommendations" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://vedyura-prototype.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Live%20Demo-0EA5E9?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Status-Prototype-22C55E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Backend-Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/Database-JSON%20Files-FFA500?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/himeshxd7/Vedyura_Prototype?style=social" />
  <img src="https://img.shields.io/github/forks/himeshxd7/Vedyura_Prototype?style=social" />
  <img src="https://img.shields.io/github/watchers/himeshxd7/Vedyura_Prototype?style=social" />
</p>

---

## ✨ About the Project

**Vedyura** is an Ayurvedic diet management prototype that helps patients receive personalized diet guidance based on health data, self-diagnosis inputs, and pulse-based biometric analysis.  
It also provides a doctor workflow where doctors can review requests, view patient diagnosis data, and generate downloadable diet chart PDFs.

This project includes:

- Patient and doctor login flows
- Self-diagnosis form
- PPG / heart-rate based health analysis
- Dominant dosha detection
- Personalized meal recommendations
- Consultation request workflow
- Diet chart PDF generation
- Personal diet assistant / chatbot-style responses

---

## 🚀 Key Features

- 🧑‍⚕️ Separate **Doctor** and **Patient** dashboards
- 📝 **Patient self-diagnosis** form for Ayurvedic profiling
- ❤️ PPG / heart-rate based health insights
- 🧠 **Dosha detection** logic: Vata, Pitta, Kapha
- 📊 BMI, calorie, and protein target estimation
- 🍛 Personalized food suggestions from an Indian food database
- 📩 Patient-to-doctor consultation request flow
- 📄 Auto-generated **diet chart PDFs**
- 🤖 Personal diet assistant for food / chart / routine queries
- 💾 JSON-based storage for users, requests, and diagnosis data
- 🎨 Clean Flask + HTML + CSS + JavaScript web interface

---

## 🧩 How It Works

```mermaid
flowchart TD
    A[Patient Sign Up / Login] --> B[Self-Diagnosis Form]
    B --> C[PPG / Pulse Analysis]
    C --> D[Health Analyzer]
    D --> E[Dosha + BMI + Calories + Protein Target]
    E --> F[Food Database Filter]
    F --> G[Personalized Diet Chart]
    G --> H[PDF Generation]

    A --> I[Consult Doctor]
    I --> J[Request Saved in JSON]
    J --> K[Doctor Dashboard]
    K --> L[Accept / Decline Request]
    K --> M[Generate Diet Chart PDF]
