# 🤖 Gemini Clone – AI Chatbot

A clean, responsive **AI Chatbot web application** built with **HTML, CSS, and JavaScript**, inspired by Google’s Gemini interface.  
This project integrates with the **Google Gemini API** (`gemini-2.5-flash`) to generate AI-powered responses with support for:
- 📝 Text input  
- 📎 File upload (images, PDF, TXT, CSV)  
- 🌙 Light/Dark theme toggle  
- 💬 Persistent chat history during the session  
- 🎨 Smooth UI/UX with typing effect animations  

---

## 🚀 Features
- **Modern UI** – Responsive design with gradient headers, smooth hover effects, and a Gemini-like layout.  
- **Smart Suggestions** – Predefined prompts for quick interactions.  
- **Typing Effect** – Bot responses appear with a typing animation.  
- **File Uploads** – Attach images, PDFs, text, or CSV files to include context in queries.  
- **Theme Toggle** – Switch between dark and light mode, with preference saved in local storage.  
- **Delete & Stop Controls** – Clear chat history or stop ongoing responses.  
- **Responsive** – Mobile-friendly design.  

---

## 🛠️ Tech Stack
- **Frontend**: HTML, CSS (Poppins font, Material Symbols, custom styles)  
- **Logic**: Vanilla JavaScript (DOM manipulation + API integration)  
- **API**: Google Gemini API (`gemini-2.5-flash`)  

---

## 📂 Project Structure

| File/Folder   | Description |
|---------------|-------------|
| `index.html`  | Main UI structure of the chatbot |
| `style.css`   | Styling & theme management (dark/light mode) |
| `script.js`   | Chat logic & API integration with Gemini |
| `gemini.svg`  | Bot avatar used in responses |
| `README.md`   | Project documentation |

---

## 🛠️ Installation

Get started in just a minute!

### 1. Clone the repository:

```bash
    git clone https://github.com/Shwati-Khilar/gemini-clone-chatbot.git
    cd gemini-clone-chatbot
```
2. Add your Gemini API key:
    Open script.js
    Replace:
    js
    Copy code
    const API_KEY = "YOUR_API_KEY_HERE";
    with your own Google API key from Google AI Studio.

3. Run the project:
    Simply open index.html in your browser.
    Or use a local server for better performance:
```bash
    npx live-server
``

## 🎯 Usage

Open the chatbot in your browser.

Type your question in the input box or click one of the predefined suggestions.

Optionally, upload a file (image, PDF, TXT, CSV) for contextual queries.

Hit send (arrow button) and watch the bot respond with a typing effect.

Use the theme toggle button to switch between light/dark modes.

Use the delete button to clear all chats or the stop button to interrupt a response.


## ⚡ Future Improvements

Add speech-to-text & text-to-speech.

Store chat history in local storage or a database.

Multi-turn context beyond session memory.

Improved error handling & UI feedback.

## 📜 Disclaimer

This project is a Gemini-inspired clone and not an official Google product.
Responses are generated using the Gemini API and may not always be accurate.

## 👩‍💻 Author
Made with ❤️ by [Shwati Khilar]