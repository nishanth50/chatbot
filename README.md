
# Flask Gemini Chatbot

A simple chatbot built using **Flask** and **Google Gemini API** to generate AI-driven responses.

## Features
- Uses **Google Gemini 1.5 Flash** for AI responses.
- Provides an interactive chat interface.
- Built with **Flask** for easy deployment.

## Installation & Setup

### 1. Clone the Repository
```sh
git clone https://github.com/YOUR_GITHUB_USERNAME/flask-gemini-chatbot.git
cd flask-gemini-chatbot
```

### 2. Create a Virtual Environment (Optional but Recommended)
```sh
python -m venv chatbot_env
source chatbot_env/bin/activate  # On Windows: chatbot_env\Scripts\activate
```

### 3. Install Dependencies
```sh
pip install flask google-generativeai
```

### 4. Set Up Google API Key
Replace `GOOGLE_API_KEY` in `app.py` with your actual API key.

### 5. Run the Application
```sh
python app.py
```

### 6. Access the Web Interface
Once the app starts, open your browser and go to:
```
http://127.0.0.1:5000/
```

## API Endpoints
- **GET /** - Renders the chat interface.
- **POST /chat** - Accepts a JSON payload `{ "message": "your question" }` and returns a chatbot response.

## File Structure
```
/flask-gemini-chatbot
│── app.py               # Flask app script
│── templates/
│   ├── index.html       # Chat interface
│── README.md            # Project documentation
```

## Contributing
Feel free to submit a pull request if you'd like to improve the chatbot.

## License
This project is licensed under the MIT License.

---
Happy coding! 🚀

