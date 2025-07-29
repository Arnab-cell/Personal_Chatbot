# ⚡ Arnab's Personal AI Chatbot 🤖

Welcome to **Arnab's Personal AI Chatbot** — a modern, personalized conversational AI interface powered by **Groq** and **LLaMA3**, built with **Streamlit**.

This chatbot combines powerful language modeling with a beautiful, customizable UI. It's designed to deliver a natural, responsive, and engaging chat experience for users.

---

## 💻 Prototype Screenshot

![Prototype UI]("C:\Users\AMIT\Downloads\Personal_Chatbot\Prototype_chatbot.png")


## 🚀 Features

- 💬 **Chat in Real Time** – AI-powered responses using Groq’s LLaMA3 model.
- 🟢 **Modern Chat UI** – Chat bubbles with avatars, custom themes, and animations.
- 🌌 **Background Image & Animated GIFs** – Personal visual branding.
- 💾 **Download Chat History** – Export chats in JSON format.
- 🧹 **Clear Chat Option** – Reset the conversation in one click.
- 🌐 **Floating Social Media Icons** – Quick links to your personal profiles.
- 📎 **Save/Load Conversations** – Easy history handling (optional).

---

## 🛠️ Tech Stack

| Component   | Tech Used                     |
|-------------|-------------------------------|
| Frontend    | Streamlit (Python-based UI)   |
| Backend     | Groq API (`llama3-8b-8192`)   |
| Styling     | Custom CSS, Font Awesome      |
| Hosting     | Localhost / Streamlit Cloud   |

---

## 📦 Installation

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/Personal_Chatbot.git
cd Personal_Chatbot


2. Set up virtual environment (optional but recommended)
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
3. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt

4. Give your personal YOUR_GROQ_API_KEY;

ini
Copy
Edit
GROQ_API_KEY=your_groq_api_key_here
▶️ Run the App
bash
Copy
Edit
streamlit run app.py
🔐 Environment Variables
Variable	Description
GROQ_API_KEY	Your Groq.com API key

📂 Folder Structure
arduino
Copy
Edit
📁 Personal_Chatbot/
│
├── app.py
├── .env
├── requirements.txt
├── assets/
│   ├── chatbot image 1.jpg
│   ├── Live chatbot.gif
│   └── AI logo Foriday.gif
└── README.md
📬 Contact
Made by Arnab Chakraborty
📧 arnabchakraborty.sam@gmail.com
🌐 LinkedIn | GitHub | Instagram
