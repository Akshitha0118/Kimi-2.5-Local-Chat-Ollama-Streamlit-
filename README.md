# 🤖 Kimi 2.5 Local Chat (Ollama + Streamlit)

A fully local AI chatbot built using **Streamlit** and **Ollama**, delivering a ChatGPT-like experience with **real-time streaming**, **zero API cost**, and **complete privacy**.

---

## 🚀 Features

* 🔐 **Fully Offline** – No API keys or internet required
* ⚡ **Real-Time Streaming** – Token-by-token responses
* 💬 **Chat Memory** – Maintains conversation history
* 🎨 **Clean UI** – Built with Streamlit chat components
* 🧠 **Local LLM** – Powered by Ollama (Kimi 2.5)

---

## 🛠️ Tech Stack

* **Frontend/UI**: Streamlit
* **Backend**: Python
* **LLM Runtime**: Ollama
* **Model**: kimi-k2.5

---

## 📂 Project Structure

```
.
├── app.py          # Main Streamlit application
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### 1. Install Ollama

Download and install from: [https://ollama.com](https://ollama.com)

Then pull the model:

```bash
ollama pull kimi-k2.5
```

---

### 2. Clone Repository

```bash
git clone https://github.com/your-username/kimi-local-chat.git
cd kimi-local-chat
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Run the App

```bash
streamlit run app.py
```

---

## 🧠 How It Works

1. User enters input via Streamlit UI
2. Message stored in session state
3. Sent to Ollama local model
4. Model generates response in streaming mode
5. UI updates token-by-token

---

## 🏗️ Architecture Diagram

```
+-------------------+
|   User Input UI   |
|  (Streamlit Chat) |
+---------+---------+
          |
          v
+-------------------+
| Session State     |
| (Chat History)    |
+---------+---------+
          |
          v
+-------------------+
|  Ollama API       |
|  (Local Model)    |
+---------+---------+
          |
          v
+-------------------+
| Streaming Output  |
| Token-by-Token    |
+---------+---------+
          |
          v
+-------------------+
| Streamlit Display |
+-------------------+
```

---

## 💡 Use Cases

* Personal AI assistant
* Offline chatbot applications
* Learning LLM integrations
* Privacy-focused AI tools

---

## 🔮 Future Improvements

* 🎙️ Voice input (Whisper)
* 📚 RAG (Document Q&A)
* 🌐 Multi-model support
* 📱 Mobile-friendly UI

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first.

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

