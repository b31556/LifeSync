
# LifeSync

**Author:** Benedek Tóth  
**Category:** Youth Individual  
**UN SDGs:** 3 - Good Health and Well-being, 10 - Reduced Inequalities  

**Presentation:** (https://docs.google.com/presentation/d/1pGS-WjRnOgouWeoJCREpAoTE3X_NyHj7/edit?usp=drive_link&ouid=111396547087337399273&rtpof=true&sd=true)


---

## Overview

**LifeSync** merges AI precision with human empathy—redefining how you track, understand, and improve your health in a connected world.  
It focuses on accessibility and inclusivity, especially for blind and visually impaired users, through gesture control, voice-first interaction, and contextual AI assistance.

> _“Because no one’s well-being should be left behind.”_

---

## Problem Statement

Inspired by the UN's Sustainable Development Goals:

- **SDG 3**: Good Health and Well-being  
- **SDG 10**: Reduced Inequalities

Chronic physical and mental health issues are skyrocketing due to poor habits and lack of real awareness. LifeSync directly tackles this with:

- AI-powered body and mental tracking  
- Real-time health feedback  
- Built-in accessibility for blind users  
- Inclusive voice-first UX  

---

## Responsible AI Usage

Your data. Your rules.  
LifeSync uses **trustworthy AI providers** (like OpenAI) while giving you full control over your personal data. Our core principle:

> Privacy first. Insight second. No compromises.

- End-to-end encryption  
- Download/delete all data anytime  
- Transparent access controls for AI components  

---

## Features

### **1. Smart Authentication**
- Manual, chatbot, or medical paper upload
- Voice-first login for blind users

### **2. Habit and Mood Tracker**
- Daily questions for trend detection
- Suicide hotline trigger on high-risk detection
- Built-in psychologist AI and mental state visualizer  
- Random comforting cat included (yes, seriously)

### **3. Nutrition Analysis**
- Food intake logging
- AI-generated blood sugar level chart (with GI estimation)
- "Remove and Re-eat" buttons
- One-click healthy recipe suggestions
- 10-day diet insights

### **4. Fitness & Health Integration**
- Optional Fitbit sync
- QR/barcode scanning for nutritional data
- Blind mode skips unnecessary third-party apps

### **5. AI Doctor Assistant**
- Full context AI chatbot  
- Web search, food/activity analysis, intake recommendation customization  
- Learns and remembers your preferences  
- Voice-enabled by default for blind users

### **6. Statistics Dashboard**
- Graphs: kcal, sugar, steps, hydration  
- Water tracker (basic but clean)
- Central Fitbit integration control

### **7. Privacy & Permissions**
- Control AI access per function  
- Delete conversations or full data logs  
- Export everything as JSON

---

## Architecture

### APIs Used:
- OpenAI API  
- Open Food Facts API  
- Fitbit API  
- Searx API  
- Private API for blood sugar estimation  

### Extensions:
- `CompCreator`, `Xreg`, `HtmlUtils`, `MareshaAES`, `ClickTools`, `KIO4_Base64`  

### For Nerds:
Technical docs, data structures, and internal logic:
[https://lifesync.jundev.eu](https://lifesync.jundev.eu)

---

## App Usage Flow


1. Authentication
2. Provide Health Info (paper upload, chatbot, manual input)
3. Install helper apps if needed (Fitbit, QR reader)
4. Use habit/mood/food/mental/fitness tools
5. Talk to the AI doctor for personalized guidance
6. Check the statistics page
7. Control privacy and permissions

For blind users:
Everything works with voice by default.


---

Acknowledgements

Békefi Prantner Erzsébet – For helping understand blood sugar level logic

Márta Szabó – For helping film the video



---

Contact

If you'd like to get in touch, ask questions, or collaborate:
Website: https://lifesync.jundev.eu


---

> Made with love, logic, and late nights by Benedek Tóth.



Let me know if you want this saved as a file or customized further (e.g., with badges, contact links, dark mode previews, etc.).

