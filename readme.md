# 🤖 Agentic AI Assistant

An AI-powered chatbot built with **Streamlit**, **LangChain**, and **Ollama**. This project demonstrates an Agentic AI workflow by enabling users to interact with a locally hosted Large Language Model (LLM) through a clean web interface.

---

## 🚀 Features

- 💬 Interactive chatbot using Streamlit
- 🤖 Local LLM integration with Ollama
- 🧠 Prompt management using LangChain
- ⚡ Fast and lightweight
- 🔒 Privacy-focused (runs locally)
- 🖥️ Simple and user-friendly interface
- 🔄 Easy to customize and extend

---

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- LangChain Community
- Ollama
- Gemma 2 (or any Ollama-supported model)

---

## 📁 Project Structure

```
Agentic-AI/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
└── screenshots/
```

---

## 📋 Prerequisites

Before running the project, make sure you have:

- Python 3.10 or later
- Ollama installed
- Git installed

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Agentic-AI.git
cd Agentic-AI
```

### Create a Virtual Environment

**Windows**

```bash
python -m venv myenv
myenv\Scripts\activate
```

**Linux/macOS**

```bash
python3 -m venv myenv
source myenv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🤖 Install Ollama

Download Ollama from:

https://ollama.com/download

Pull the Gemma model:

```bash
ollama pull gemma2:2b
```

Start Ollama:

```bash
ollama serve
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

Open your browser and visit:

```
http://localhost:8501
```

---

## 💡 How It Works

1. User enters a question.
2. Streamlit receives the input.
3. LangChain formats the prompt.
4. Ollama sends the prompt to the local LLM.
5. The generated response is displayed on the web interface.

---

## 📸 Screenshots

Add your screenshots inside the `screenshots` folder.

Example:

```
screenshots/home.png
```

---

## 📦 Requirements

```
streamlit
langchain
langchain-community
langchain-core
ollama
```

or install directly:

```bash
pip install streamlit langchain langchain-community langchain-core ollama
```

---

## 🔮 Future Enhancements

- ✅ Multi-Agent AI
- ✅ RAG (Retrieval-Augmented Generation)
- ✅ PDF Chat
- ✅ Chat History
- ✅ Memory Support
- ✅ Web Search Integration
- ✅ Voice Assistant
- ✅ Image Understanding
- ✅ Docker Deployment
- ✅ Cloud Deployment

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Added new feature"
```

4. Push to GitHub.

```bash
git push origin feature-name
```

5. Create a Pull Request.

---

## 👨‍💻 Author

**Aditya Jadhav**

GitHub: https://github.com/YOUR_USERNAME

LinkedIn: https://linkedin.com/in/YOUR_LINKEDIN

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

---

## 📄 License

This project is licensed under the MIT License.
