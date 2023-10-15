# Chatbot Project

## Overview
This project is a simple chatbot created using HTML, CSS, JavaScript, and the OpenAI API. The chatbot interacts with users, providing responses based on AI-driven natural language processing. It serves as a fun and educational example of how to integrate AI into web applications.

![Chatbot Demo](/path-to-demo-gif.gif)

## Deployment Link - https://openaichatbotapp.netlify.app/

## Features
- Real-time chat interface.
- AI-driven responses powered by the OpenAI API.
- Customizable chatbot persona and interactions.

## Usage
1. Clone this repository:
git clone https://github.com/yourusername/chatbot-project.git
cd chatbot-project


2. Open `index.html` in your web browser.

3. Start chatting with the chatbot.

## Configuration
To configure the chatbot's behavior, you can customize the OpenAI API key and adjust persona details in the JavaScript code (`script.js`).

```javascript
// Configure OpenAI API
const openai = new OpenAI({
key: 'your-openai-api-key-here',
language: 'en', // or your preferred language
});

// Define chatbot persona and interactions
const chatbotPersona = {
name: 'ChatBot',
avatar: '/path-to-avatar.png',
};

