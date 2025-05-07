# Digital Sage - AI Chatbot


## Overview

Digital Sage is a modern, feature-rich AI chatbot powered by Google's Gemini API. With a sleek dark theme interface, this chatbot offers an intelligent conversation experience that can be easily integrated into your website or application.

## Features

- 🤖 **AI-Powered Responses**: Leverages the powerful Gemini 2.0 Flash API
- 🌙 **Dark Theme**: Sleek, modern dark interface
- 📎 **File Upload**: Share images with the bot
- 😀 **Emoji Picker**: Express yourself with a wide range of emojis
- 💬 **Chat History**: Maintains conversation context
- ⚡ **Loading Animations**: Smooth transition while the bot thinks
- 📱 **Responsive Design**: Works on all devices
- 🔄 **Toggle Functionality**: Easily show/hide the chatbot

## Getting Started

### Prerequisites

- A Gemini API key (free tier available)
- Basic knowledge of HTML, CSS, and JavaScript

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/ShashiniMadhu/AI_Chatbot.git
   ```

2. Navigate to the project directory:
   ```
   cd AI_Chatbot
   ```

3. Open `script.js` and replace the API key with your own:
   ```javascript
   const API_KEY = "YOUR_GEMINI_API_KEY";
   ```

4. Open `index.html` in your browser or deploy to your web server.

## Usage

1. Click the chat icon to open the chatbot
2. Type your message in the input field
3. Use the emoji picker to add emotions to your message
4. Upload images using the attachment icon
5. Press Enter or click the send button to send your message

## Customization

You can easily customize Digital Sage to match your branding:

- Modify the colors in `style.css`
- Change the bot avatar and logo in `index.html`
- Adjust the welcome message in the HTML
- Customize response handling in `script.js`

## API Configuration

The chatbot uses Google's Gemini 2.0 Flash model. To customize the API usage:

1. Get your API key from [Google AI Studio](https://makersuite.google.com/)
2. Update the API key and URL in `script.js`
3. Modify the `generateBotResponse` function to change how responses are handled

## Acknowledgments

- Google Gemini API for powering the AI responses
- Emoji Mart for the emoji picker functionality

---

⭐ If you found this project useful, please consider giving it a star on GitHub! ⭐
