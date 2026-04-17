# 🤖 AI Chatbot using Ollama + LangChain + Streamlit

An interactive AI chatbot built using **LangChain**, **Ollama (LLaMA model)**, and **Streamlit**.
This project runs a Large Language Model locally, allowing you to chat without relying on paid APIs.

---

## 🚀 Features

- 🧠 Local LLM powered by Ollama (LLaMA model)
- ⚡ Fast and interactive UI using Streamlit
- 🔗 LangChain integration for prompt chaining
- 🔒 No external API dependency (runs offline)
- 📊 Easy to customize and extend

---

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- Ollama (LLaMA model)
- dotenv (for environment variables)

---

## 📂 Project Structure

```
.
├── ollama.py              # Main Streamlit app
├── .env               # Environment variables
├── requirements.txt   # Dependencies
└── README.md          # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

---

### 2️⃣ Create virtual environment

```
python -m venv venv
```

Activate it:

**Windows**

```
venv\Scripts\activate
```

**Mac/Linux**

```
source venv/bin/activate
```

---

### 3️⃣ Install dependencies

```
pip install -r requirements.txt
```

---

### 4️⃣ Install and run Ollama

Download Ollama from: https://ollama.com

Start Ollama server:

```
ollama serve
```

Pull the LLaMA model:

```
ollama pull llama2
```

---

### 5️⃣ Setup environment variables

Create a `.env` file and add:

```
LANGCHAIN_API_KEY=your_api_key_here
```

---

### 6️⃣ Run the application

```
streamlit run app.py
```

---

## 💡 Usage

- Enter any query in the input box
- The chatbot will respond using the local LLaMA model

---

## 🧠 How it Works

1. User input is captured via Streamlit UI
2. LangChain formats the prompt
3. Ollama runs the LLaMA model locally
4. Response is parsed and displayed

---

## ⚠️ Notes

- Ensure Ollama is running before starting the app
- Requires a system with sufficient RAM for LLM execution
- First model download may take time

---

## 📌 Future Improvements

- Add chat history memory
- Support multiple models
- UI enhancements
- Deploy with Docker

---

## 🤝 Contributing

Feel free to fork this repo and submit pull requests!

---

---

## 👨‍💻 Author

Shubhi Jain

---
