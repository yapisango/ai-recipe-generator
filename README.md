🧑🏽‍🍳 AI-Powered Recipe Generator (Chef Claude)

An AI-powered React application that generates recipes based on available ingredients using modern AI APIs.

Built to demonstrate frontend engineering + API integration + real-world problem solving.

🚀 Live Demo

👉 https://scintillating-lebkuchen-824685.netlify.app/

🌟 Key Features
Generate recipes from user-provided ingredients
AI-powered responses using Claude (primary) + fallback model
Responsive and clean UI
Markdown-rendered recipe formatting
Error handling with fallback logic
Dynamic state management using React Hooks
🧠 Problem Solved

Deciding what to cook with limited ingredients can be frustrating.

This app solves that by:

Taking simple ingredient inputs
Generating structured, easy-to-follow recipes
Ensuring reliability with fallback AI logic
🛠 Tech Stack
Frontend: React, JavaScript (ES6), Vite
AI Integration: Anthropic Claude API, Mistral (fallback)
UI Rendering: React Markdown
Environment: Vite (.env for API keys)
⚙️ How It Works
User inputs ingredients
App sends request to AI API
Claude generates a recipe
If unavailable → fallback model is used
Recipe is formatted and displayed
📂 Project Structure
src/
 ├── Main.jsx
 ├── ai.js
 └── components/
     ├── IngredientsList.jsx
     └── ClaudeRecipe.jsx
📸 Preview

💡 What I Learned
Integrating AI APIs into frontend applications
Managing asynchronous data and API failures
Designing user-friendly, responsive interfaces
Structuring scalable React applications
👨🏽‍💻 Author

Sango Mabhuti Yapi
Frontend Developer | BSc Computer Science & Chemistry

🌐 Portfolio: https://yapisango-portfolio.netlify.app
💻 GitHub: https://github.com/yapisango