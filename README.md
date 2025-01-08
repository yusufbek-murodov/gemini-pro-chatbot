# Gemini-Pro Chatbot

Welcome to the **Gemini-Pro Chatbot** project! This is a simple, interactive chatbot application built with Streamlit and powered by Google's Gemini-Pro AI. The chatbot allows users to engage in natural conversations using the state-of-the-art generative AI model.

---

## Features

- Chat with the Gemini-Pro AI directly from your browser.
- Clean and user-friendly interface designed with Streamlit.
- Maintains conversational context using session state.
- Customizable settings for enhanced user experience.

---

## Tech Stack

- **Python**: The core programming language used.
- **Streamlit**: Framework for building the chatbot's interactive web interface.
- **Google Gemini-Pro**: AI model used for generating responses.
- **dotenv**: For managing environment variables securely.

---

## 🌟 Check Out the Live Demo  

Experience the Gemini-Pro Chatbot in action:  
[**Gemini-Pro Chatbot Live Demo**](https://gemini-assistant-ai.streamlit.app/)

---

## Prerequisites

Before running the project, ensure you have:

- Python 3.8 or above installed on your system.
- A Google Gemini-Pro API key.

---

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/gemini-pro-chatbot.git
   cd gemini-pro-chatbot
   ```

2. Create a virtual environment and activate it:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Set up your environment variables:

   - Create a `.env` file in the project root directory.
   - Add the following line, replacing `YOUR_GOOGLE_API_KEY` with your actual API key:
     ```env
     GOOGLE_API_KEY=YOUR_GOOGLE_API_KEY
     ```

---

## Running the Application

Start the Streamlit app using the following command:

```bash
streamlit run app.py
```

The chatbot will open in your default web browser. If not, visit `http://localhost:8501` manually.

---

## Usage

1. Enter your query in the input box labeled **"Ask Gemini-Pro..."**.
2. View the chatbot's response in the chat interface.
3. The conversation history is displayed for context.

---

## Project Structure

```
.
├── app.py               # Main application script
├── requirements.txt     # Python dependencies
├── .env.example         # Example environment variables file
└── README.md            # Project documentation
```


