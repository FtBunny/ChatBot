This is a chatbot application built using JavaScript, HTML, and CSS. It utilizes the Google Cloud Natural Language API to generate responses to user input.

#Features

User can send text messages to the chatbot
Chatbot responds with generated text based on user input
User can upload files to the chatbot
Chatbot displays uploaded files
Emoji picker for user to add emojis to their messages

#Requirements

Node.js (for development)
Google Cloud Natural Language API key
Web browser (for testing)

#Installation

Clone the repository: git clone https://github.com/your-username/chatbot-application.git
Install dependencies: npm install
Create a new file named config.js and add your Google Cloud Natural Language API key:
javascript
const API_KEY = 'YOUR_API_KEY_HERE';
const API_URL = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${API_KEY}`;
Start the application: npm start

#Usage

Open the application in a web browser: http://localhost:3000
Send a message to the chatbot by typing in the input field and pressing enter
Upload a file to the chatbot by clicking the file upload button
Use the emoji picker to add emojis to your messages

#API Documentation

The chatbot uses the Google Cloud Natural Language API to generate responses. The API endpoint is:

https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent
The API request body should contain the user's input message and any uploaded files.
