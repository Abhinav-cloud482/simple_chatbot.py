# simple_chatbot.py
This project is a rule-based chatbot built in Python that uses regular expressions to match user keywords and provide predefined responses. It supports case-insensitive input, includes a default reply for unknown queries, and runs through an interactive command-line interface until the user enters **"bye"**.


# 🤖 Rule-Based Chatbot in Python

A simple and interactive **rule-based chatbot** built using Python that responds to user queries by identifying keywords with regular expressions and returning predefined responses. This project demonstrates basic Natural Language Processing (NLP) concepts, pattern matching, and conversational logic.

---

## 📌 Features

- 💬 Interactive command-line chatbot interface
- 🔍 Keyword-based response detection using Regular Expressions (`re`)
- 🔤 Case-insensitive user input processing
- ⚡ Instant predefined responses for common queries
- 🛡️ Default fallback response for unknown inputs
- 🚪 Exit functionality using the `"bye"` command

---

## 🛠️ Technologies Used

- **Python 3**
- **Regular Expression (`re`) Module**

---

## 📂 Project Structure

```
Rule-Based-Chatbot/
│
├── chatbot.py        # Main chatbot application
├── README.md         # Project documentation
└── requirements.txt  # Project dependencies (if required)
```

---

## 🚀 Getting Started

### Prerequisites

Make sure Python is installed on your system:

```bash
python --version
```

---

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/rule-based-chatbot.git
```

2. Navigate to the project directory:

```bash
cd rule-based-chatbot
```

3. Run the chatbot:

```bash
python chatbot.py
```

---

## 💻 Usage

Start chatting with the bot through the terminal:

```
Chatbot: Hello! I'm here to assist you. (type 'bye' to exit)

You: hello
Chatbot: Hi there! How can I assist you today?

You: how are you
Chatbot: I'm just a bot, but I'm doing great! How about you?

You: bye
Chatbot: Goodbye! Have a great day!
```

---

## 🧠 How It Works

1. User enters a message through the command line.
2. The input is converted to lowercase for consistent matching.
3. Regular expressions check whether predefined keywords exist in the message.
4. The chatbot returns the corresponding response.
5. If no keyword matches, a default response is displayed.

---

## 🔮 Future Improvements

- Add machine learning-based response generation
- Integrate Natural Language Processing (NLP) libraries
- Store conversations using databases
- Add voice input and speech output support
- Develop a web-based chatbot interface

---

## 👨‍💻 Author

**Your Name**  
GitHub: [Your GitHub Profile](https://github.com/your-username)

---

## 📜 License

This project is open-source and available under the **MIT License**.
