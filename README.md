# 🧠 Mind Mate-A Self Help & Mental Health Companion

**Mind Mate** is a web-based platform designed to assist individuals in recognizing, understanding, and managing **depression** through AI-powered tools, CBT-based therapy, and other engaging activities. Basically we had designed a website, where indivuals can get initial support from our platform, therapist, chatbot, This project was developed by a me and my amazing team members during **Enkryptia – The Hackathon**, held at **Government Polytechnic Nagpur**.

---

## ❓ What is Depression?

Depression is a common and serious mental health condition that negatively affects how you feel, think, and act. It can lead to emotional and physical problems, decreasing a person’s ability to function at home, work, or in society.

### 🚨 Common Symptoms in Women:

- 😞 Depressed mood  
- 💔 Loss of interest or pleasure in activities  
- 😩 Fatigue and low energy  
- 😔 Feelings of guilt, hopelessness, or worthlessness  
- 🍽️ Appetite and weight changes  
- 😴 Sleep disturbances  
- 🧠 Difficulty concentrating  
- ⚠️ Suicidal thoughts or recurrent thoughts of death  

---

## 🧪 Depression Screening Test

We provide a **3-minute depression screening test** that evaluates the user's mental health condition.  
- 🔒 All results are private  
- ✅ User-friendly and safe to use  
- 🧾 Generates severity-based results for further action

---

## 🧠 Cognitive Behavioral Therapy (CBT)

### 🧩 Cognitive Restructuring  
Users can enroll in a **14-16 week therapy plan**, where they are connected with verified therapists.  
- 🧑‍⚕️ Therapist assigned locally based on user’s location  
- 📞 Sessions via phone call or in-person meetings  
- 🔄 Weekly progress and feedback tracking

### 🎨 Behavioral Activation – *Draw My Life*  
Patients receive sketch-based weekly challenges using an in-browser **JavaScript-powered sketchpad**.  
- ✏️ Draw tasks get more engaging & difficult each week  
- 🧱 Helps break down negative behavior and rebuild confidence  
- 🎯 Encourages consistency through creativity

---
### 🤖 Technologies Used
- Backend: Python, Django, Flask
- Frontend: HTML5, CSS3, JavaScript
- Chatbot: RAG (Retrieval-Augmented Generation)
- Drawing Module: JavaScript-based sketchpad
---

## ⚙️ Installation & Setup

```bash
# Step 1: Install all dependencies
pip install --upgrade -r requirements.txt

# Step 2: Load initial data (Therapists & Drawing Challenges)
python manage.py loaddata therapist.json
python manage.py loaddata drawing_challenges.json 

# Step 3: Run the development server
python manage.py runserver
```
## 👥 Contributors

- Tanay Tonpe
- Pushkar Jadhav
- Palak Zade
---

## 🤝 Contribute with Heart

We welcome ideas, suggestions, and improvements!  
Raise an issue, fork the repo, or submit a pull request — your contribution could help someone in need. 💙

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
---

## ⭐ Show Some Love

If you like this project, give us a ⭐ on GitHub — it keeps us motivated to build more helpful things!
