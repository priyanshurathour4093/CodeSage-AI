# CodeSage-AI  

An AI-powered code reviewer web app that analyzes your code, detects bad practices, and provides instant feedback with improvement suggestions.  

---

## 🚀 Features  
- AI-driven reviews using Gemini API  
- Real-time detection of issues and recommendations  
- Minimal, no-login interface  
- Syntax highlighting with PrismJS  
- Feedback rendered in Markdown  

---

## 🛠️ Tech Stack  
- **Frontend**: React, PrismJS, Markdown  
- **Backend**: Node.js, Express.js  
- **AI Model**: Gemini API via `@google/generative-ai`  

---
### Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/codesage-ai.git
   cd codesage-ai
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create an .env file in the backend and add:: 
   ```env
   GEMINI_API_KEY=your_api_key_here
   ```
4. Run the backend:  
   ```bash
   cd BackEnd
   npx nodemon
   ```
5. Run the frontend:  
   ```bash
   cd Frontend
   npm run dev
   ```

---
🎯 Usage

1-Open the app in your browser.
2-Paste or type code in the editor.
3-View AI-generated feedback with issues and suggestions.
