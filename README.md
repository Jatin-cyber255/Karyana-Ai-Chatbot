# Karyana Chatbot

A modern, animated, and professional chatbot web app for a local karyana (grocery) store.  
This chatbot answers only grocery-related questions in the user's language, with short, shop-like replies.

## Features

- Answers only karyana/grocery-related questions
- Detects and replies in the user's language (Hindi/English)
- Modern, responsive, and animated UI (black & blue theme)
- Shows typing animation for the bot
- Built with Node.js (Express) backend and HTML/CSS/JS frontend
- Uses Groq API (Llama 3 model) for AI responses

## How to Run

1. **Clone this repository:**
   ```bash
   git clone https://github.com/Jatin-cyber255/Karyana-Ai-Chatbot.git
   cd karyana-chatbot
   ```

2. **Install backend dependencies:**
   ```bash
   npm install
   ```

3. **Add your Groq API key:**
   - Create a `.env` file in the root folder:
     ```
     GROQ_API_KEY=your_groq_api_key_here
     ```

4. **Start the backend server:**
   ```bash
   node server.js
   ```

5. **Open `done.html` in your browser.**


## Technologies Used

- Node.js, Express.js
- Groq API (Llama 3)
- HTML, CSS (custom), JavaScript
- Font Awesome, Google Fonts

## Project Structure

```
karyana-chatbot/
│
├── server.js
├── index.html
├── .env
├── package.json
└── README.md
```

## Credits

- Developed by Jatinkumar 
- UI inspired by modern chat apps.

---

**Note:**  
This chatbot is for educational/demo purposes.  
You can customize item rates and shop details in `server.js` as per your needs.
