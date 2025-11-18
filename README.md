# mental-health-agent
Student Mental-Health Support Agent for Kaggle Agents for Good competition

This repository contains my project submission for the **Kaggle “Agents for Good” Competition (2025)**.  
The project aims to support students and working professionals by providing a **rule-based AI mental-health support agent** that:

- Understands emotional signals  
- Measures severity of distress  
- Detects crisis or self-harm related messages  
- Provides safe, supportive responses  
- Encourages reaching out to real-world help  

This agent is designed to **promote emotional well-being** in a simple, safe, and responsible way.

---

## 🚀 Features

### ✔ Severity Scoring System  
The agent analyzes user messages and assigns a severity score from **0 to 12**, based on emotional keywords:

- Stress → +2  
- Anxiety → +3  
- Low mood / depression → +4  
- Crisis phrases → immediate crisis (12)

### ✔ Emotion Classification  
Detects:
- Stress  
- Anxiety  
- Low mood  
- Crisis states  
- Or “unclear” emotional state

### ✔ Crisis Detection  
If the message includes crisis keywords like:
- *“ending my life”*  
- *“I want to die”*  
- *“life is pointless”*  

The agent triggers an **emergency response** encouraging the user to seek immediate help.

### ✔ Supportive Responses  
Based on severity:
- Mild responses  
- Moderate support  
- High-emotion reassurance  
- Crisis emergency guidance  

### ✔ Safe & Ethical  
- No diagnosis  
- No medical advice  
- Encourages talking to real people offline  
- Includes safety disclaimers
- ---

## 📄 Notebook  
You can view the full Kaggle notebook here:

[Calm Compass – Student Mental-Health Support Agent](https://www.kaggle.com/code/charanvegaraju/calm-compass)



