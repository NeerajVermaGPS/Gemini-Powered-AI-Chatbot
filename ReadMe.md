<img src="files/Assistant.png" width="80px">

# Python Based AI Chatbot

This project is a simple AI chatbot built using Python, Tkinter for the GUI, and Google Gemini API for AI-based conversations. It allows users to interact with a virtual assistant by typing messages, with responses generated through the AI model.

## Features
- **Interactive GUI**: Created using Tkinter for a clean and user-friendly interface.
- **AI Conversations**: Utilizes Google Gemini API to generate AI-based responses.
- **Real-time Interaction**: Users can input text and receive responses dynamically.
- **Simple Design**: Lightweight design for easy usage and integration.

## Technologies Used
- **Python**: Core programming language used to develop the chatbot.
- **Tkinter**: For building the graphical user interface.
- **PIL (Pillow)**: To handle and display images in the interface.
- **Google Gemini API**: For generating AI-based text responses.

## Project Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/NeerajVermaGPS/Gemini-Powered-AI-Chatbot.git
   cd Gemini-Powered-AI-Chatbot
   ```

2. Install the required dependencies:
   ```bash
   pip install tkinter pillow google-generativeai
   ```

3. Replace the `API_KEY` in the `configure_gemini_api()` function with your Google Gemini API key:
   ```python
   genai.configure(api_key='YOUR_API_KEY')
   ```

4. Run the chatbot:
   ```bash
   python app.py
   ```

## How to Use
- Enter your message in the input field at the bottom of the window.
- Click the "Send" button to send your message.
- The AI assistant will respond in the display area above the input field.

## Future Enhancements
- Add support for **voice interaction**.
- Implement **multi-language** support.
- Improve AI capabilities using **deep learning** models.