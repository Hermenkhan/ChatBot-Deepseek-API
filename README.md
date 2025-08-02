# ChatBot-Deepseek-API

This project is a lightweight and responsive AI chatbot web app built using HTML, Bootstrap, and JavaScript, integrated with the OpenRouter API to process and return AI-generated responses using the DeepSeek LLaMA 70B model.

🔍 Features
Simple and elegant Bootstrap-based UI.

AI interaction using OpenRouter’s deepseek-r1-distill-llama-70b:free model.

Markdown rendering of AI responses using marked.js.

Real-time user input processing and display.

📦 Tech Stack
Frontend: HTML5, CSS3, Bootstrap 4.3.1

JavaScript: Vanilla JS + Fetch API

API: OpenRouter AI

Markdown Parser: marked.js

🚀 How It Works
User enters a message in the input field.

On clicking "Ask!", the input is sent to the OpenRouter endpoint via fetch().

The chatbot receives and parses the AI response (in Markdown format).

Markdown is rendered in the #response container for a clean display.

⚙️ Setup Instructions
Clone or download this repository.

Replace "<your api key>" in the script with your OpenRouter API key.

Optionally configure:

HTTP-Referer with your domain name.

X-Title with your site/app name.

Open index.html in your browser and start chatting.

🛡️ Warning
Do not expose your API key in production. Use a backend proxy or environment variables for secure deployment.

