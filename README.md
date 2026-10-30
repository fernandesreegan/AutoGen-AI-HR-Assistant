
# 🤖 AutoGen AI HR Assistant

An interactive AI-powered HR Assistant built using **Microsoft AutoGen, OpenAI, and Streamlit** to generate customized job descriptions.

## 🚀 Features

- 🤖 AI-powered job description generation
- 🎯 Dynamic job role selection
- 📊 Experience levels: Junior, Mid-Level, Senior & Lead
- 📝 Customizable output line count
- ⚡ Async execution using `asyncio` and `run_stream()`
- 🔐 Secure API key management using `.env`
- 💻 Interactive Streamlit web interface

## 🛠️ Tech Stack

- **Python** – Core programming
- **AutoGen** – AI Agent framework
- **OpenAI** – LLM integration
- **Streamlit** – Web interface
- **python-dotenv** – API key management

## ⚙️ Installation

### 1. Clone Repository

```bash
git clone https://github.com/fernandesreegan/AutoGen-AI-HR-Assistant.git
cd AutoGen-AI-HR-Assistant
```

### 2. Create Virtual Environment

```bash
py -3.12 -m venv venv
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure API Key

Create a `.env` file:

```env
OPENAI_API_KEY=your_openai_api_key_here
```

### 5. Run Application

```bash
streamlit run app.py
```

Open: http://localhost:8501

## 📁 Project Structure

```text
AutoGen-AI-HR-Assistant/
├── app.py
├── hr_agent.py
├── requirements.txt
├── .env
├── .gitignore
└── README.md
```

## 📚 Key Learnings

✅ AutoGen AssistantAgent Configuration  
✅ OpenAI LLM Integration  
✅ Async Agent Execution & Streaming  
✅ Streamlit UI Development  
✅ Prompt Engineering & API Security  

## 👨‍💻 Author

**Fernandes Reegan**  
GitHub: https://github.com/fernandesreegan

---

⭐ If you find this project useful, give it a star!
