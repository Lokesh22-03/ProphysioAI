﻿# ProphysioAI
Sure! Here's a **simple and clear README** you can use for your **ProPhysioAI** project:  

---

# 🏃‍♂️ ProPhysioAI - Injury Risk, Rehab & Diet Coach

**ProPhysioAI** is an AI-powered mobile and web app that helps athletes:  
- Predict their **injury risk**  
- Get **personalized rehabilitation** and **exercise plans**  
- Generate **customized diet plans** for faster recovery and better performance

It uses the power of **OpenAI's GPT-4** to give expert-level advice instantly!

---

## ✨ Features
- 📋 **Athlete Info Form** – Enter your age, weight, sport, injury history, diet preference, and fitness goal.
- 🧠 **Injury Risk Prediction** – AI predicts if you're at high or low risk of injury.
- 🏥 **Rehabilitation Plans** – Customized treatment advice if you have a past injury.
- 🥗 **Diet Plan Generator** – Personalized meal plans based on your goals and health.
- 📈 **BMI Calculation** – Automatic BMI status with color-coded health indication.

---

## 🛠️ Technologies Used
- **React Native** (for mobile app)
- **Expo** (for easy app development)
- **Streamlit** (for web app prototype)
- **Firebase** (for saving athlete data)
- **OpenAI GPT-4 API** (for injury, rehab, and diet AI responses)
- **Python** (only for the web app using Streamlit)

---

## 📱 Mobile App (React Native + Expo)
- Build UI in `.tsx` (TypeScript + JSX)
- Collect athlete info
- Save data to Firebase
- Send athlete data to OpenAI GPT-4 for prediction and advice
- Show injury risk, rehab plans, and diet plans to the user

---

## 🌐 Web App (Streamlit)
- Simple web version for testing
- Collect user inputs
- Predict injury risk
- Show rehab and diet advice using OpenAI API
- Created using Python

---

## 🚀 How to Run the Project
### Mobile App:
1. Install Expo CLI:  
   `npm install -g expo-cli`
2. Clone the project.
3. Run:  
   `expo start`
4. Scan the QR code using the **Expo Go app** on your phone!

---

## 📂 Folder Structure
```
/prophysioai-mobile
  /screens
    - HomeScreen.tsx
    - ChatBotScreen.tsx
  /components
    - AthleteForm.tsx
  App.tsx
  firebaseConfig.ts
  ...
```

---

## 📄 Requirements
- Node.js installed
- Expo CLI installed
- Firebase account (for database)
- OpenAI API Key (for GPT-4)

---

## 🙏 Credits
- **OpenAI** for GPT-4 intelligence
- **Firebase** for secure database storage
- **Expo & React Native** for quick mobile app development

---

> Built with ❤️ to help athletes stay healthy and perform at their best!

---

Would you also like me to give a **shorter** version too (for GitHub)?  
🚀 I can give both long and short versions if you want!
