# 📚 AI Study Assistant

An AI-powered Study Assistant built using **Python**, **Gradio**, and **Google Gemini**. This application helps students understand concepts, ask questions, and receive AI-generated explanations through an easy-to-use web interface.

---

## 🚀 Features

* 🤖 AI-powered question answering using Google Gemini
* 📖 Concept explanations in simple language
* 💡 Interactive Gradio-based user interface
* ⚡ Fast and responsive
* 🌐 Ready for cloud deployment

---

## 🛠️ Tech Stack

* **Python**
* **Gradio**
* **Google Gemini API** (`google-genai`)
* **python-dotenv** (for local environment variables)

---

## 📂 Project Structure

```text
AI-Study-Assistant/
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/AI-Study-Assistant.git
cd AI-Study-Assistant
```


### 2. Install the dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Configure the API Key

Create a `.env` file in the project root:

```env
GOOGLE_API_KEY=YOUR_GOOGLE_GEMINI_API_KEY
```

Then load it in your Python application:

```python
from dotenv import load_dotenv
import os

load_dotenv()

API_KEY = os.getenv("GOOGLE_API_KEY")
```

---

## ▶️ Run the Application

```bash
python app.py
```

The application will start locally and can be accessed in your browser.

---

## ☁️ Deployment

This project can be deployed on platforms such as:

* Render
* Railway
* Google Cloud Run
* Oracle Cloud Free Tier

For Render:

* Build Command:

```bash
pip install -r requirements.txt
```

* Start Command:

```bash
python app.py
```

Remember to add your `GOOGLE_API_KEY` as an environment variable in the deployment platform.

---


---

## 🔮 Future Improvements

* 📄 PDF upload and analysis
* 📝 AI-generated notes
* ❓ Quiz generation
* 📚 Flashcard generation
* 💬 Chat history
* 🌙 Dark mode
* 📥 Export responses as PDF

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, create a new branch, and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Saran Kumar Kurapati**

* GitHub: https://github.com/sarankumar1464

If you found this project helpful, consider giving it a ⭐ on GitHub!
