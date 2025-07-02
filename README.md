# sentiment-transformer
# 🤖 Sentiment Chatbot – Local NLP Assistant

A fully local, web-based chatbot that detects the **sentiment** of user inputs and responds with empathy.  
Built using **Hugging Face Transformers**, **Flask**, and **LangChain**, this project simulates a mood-aware conversational assistant without needing any API keys or cloud models.

![Chatbot UI](./screenshot.png) <!-- Optional: replace with your screenshot file -->

---

## 🚀 Features

- 🔒 **Runs 100% Locally** – No OpenAI/Hugging Face API keys required
- 🧠 **Sentiment Detection** – Uses a fine-tuned **DistilBERT** model
- 💬 **Contextual Memory** – Remembers conversation using **LangChain**
- 🌓 **Dark Mode UI** – Includes toggle switch
- 🧑‍💻 **Responsive Web Interface** – Built using **HTML/CSS/JS**
- 🖼️ **Bot Profile Image** – For realistic touch

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Flask  
- **NLP Model**: DistilBERT (via Hugging Face Transformers)  
- **Memory & Flow**: LangChain  
- **Deployment**: Localhost (No internet required)

---

## 🧠 How It Works

1. You type a message (e.g., _"I had a bad day..."_)
2. The model classifies it as **positive**, **neutral**, or **negative**
3. The chatbot responds with an appropriate message and emoji
4. Past messages are stored using LangChain memory

---

## 📂 Project Structure
sentiment-transformer/
│
├── app.py # Flask backend
├── templates/
│ └── index.html # Chatbot UI
├── static/
│ ├── style.css # Custom styling
│ └── script.js # Frontend logic
├── model/
│ └── sentiment_model/ # DistilBERT model directory
├── requirements.txt # Python dependencies
└── README.md # Project documentation

---

## ▶️ How to Run

1. Clone the repo  
git clone https://github.com/NItin6803/sentiment-transformer.git
cd sentiment-transformer

2. Install dependencies  
pip install -r requirements.txt

3. Run the app  
python app.py

4. Open in browser  
http://localhost:5000

----

## 📌 Future Enhancements

- Add voice input/output  
- Save chat history locally  
- Train sentiment model on custom data  
- Add multi-language support
  
---

## 👨‍💻 Author

**Nitin B**  
🔗 [LinkedIn](https://linkedin.com/in/nitin-b-ab7b93218)  
📧 bnitinsharma68@gmail.com

---

## ⭐️ Show Some Love

If you like this project, please give it a ⭐️ on [GitHub](https://github.com/NItin6803/sentiment-transformer)!




