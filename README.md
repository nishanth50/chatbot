# Healthcare Chatbot

A simple healthcare chatbot built using **Streamlit**, **NLTK**, and **Transformers**. This chatbot provides responses to basic healthcare-related queries and generates AI-driven text for other inputs.

## Features
- Provides predefined responses for common healthcare-related questions (symptoms, appointments, medication advice).
- Uses **DistilGPT-2** for AI-generated responses.
- Built with **Streamlit** for an easy-to-use web interface.

## Installation & Setup

### 1. Clone the Repository
```sh
git clone https://github.com/YOUR_GITHUB_USERNAME/healthcare-chatbot.git
cd healthcare-chatbot
```

### 2. Create a Virtual Environment (Optional but Recommended)
```sh
python -m venv chatbot_env
source chatbot_env/bin/activate  # On Windows: chatbot_env\Scripts\activate
```

### 3. Install Dependencies
```sh
pip install -r myrequirements.txt
```

### 4. Download Required NLTK Data
```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

### 5. Run the Application
```sh
streamlit run app.py
```

## Usage
1. Open the Streamlit app in your browser (usually at `http://localhost:8501/`).
2. Type your healthcare-related question.
3. Click "Submit" to get a response.

## File Structure
```
/healthcare-chatbot
│── app.py               # Main chatbot script
│── myrequirements.txt   # Required dependencies
│── README.md            # Project documentation
```

## Contributing
Feel free to submit a pull request if you'd like to improve the chatbot.

## License
This project is licensed under the MIT License.

---
Happy coding! 🚀


