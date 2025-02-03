# AI Chatbot for Call Center Intelligence

## Overview
The **AI Chatbot for Call Center Intelligence** is designed to enhance customer service by automating responses, handling inquiries efficiently, and reducing wait times. This chatbot uses **FastAPI** for the backend, **Streamlit** for the frontend, and integrates **LangChain** and **Gemini API** to provide intelligent and context-aware conversations.

## Features
- **Real-time Interaction**: Engages customers instantly with automated yet human-like responses.
- **Memory Retention**: Remembers past interactions to maintain context and provide relevant replies.
- **Agent-Based Responses**: Uses intelligent agents for handling complex queries and decision-making.
- **Monitoring & Debugging**: Integrated with **LangSmith** for testing, debugging, and fine-tuning responses.
- **Secure Authentication**: Implements user authentication to manage interactions securely.
- **Customizable Workflow**: Adaptable to different industries and customer service needs.

## Tech Stack
- **Backend**: FastAPI
- **Frontend**: Streamlit
- **AI & NLP**: LangChain, Gemini API
- **Monitoring & Debugging**: LangSmith

## Installation & Setup
### Prerequisites
- Python 3.8+
- Virtual environment (optional but recommended)
- API keys for Gemini and LangSmith

### Steps
1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-repo/ai-callcenter-chatbot.git
   cd ai-callcenter-chatbot
   ```
2. **Create a Virtual Environment & Install Dependencies**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   pip install -r requirements.txt
   ```
3. **Set Up Environment Variables**
   Create a `.env` file and add your API keys:
   ```
   GEMINI_API_KEY=your_gemini_api_key
   LANGSMITH_API_KEY=your_langsmith_api_key
   ```
4. **Run the Backend (FastAPI Server)**
   ```sh
   uvicorn app:app --host 0.0.0.0 --port 8000
   ```
5. **Run the Frontend (Streamlit UI)**
   ```sh
   streamlit run frontend.py
   ```

## Usage
1. Open the Streamlit UI in your browser.
2. Log in to the chatbot interface.
3. Start chatting with the AI chatbot.
4. The chatbot will handle customer queries and provide smart responses.

## Future Enhancements
- Voice assistant integration
- Sentiment analysis for better customer understanding
- Multi-language support
- CRM system integration

## Contributors
- **Bondili Rishit Singh** - [GitHub](https://github.com/Rishit211) | [LinkedIn](https://linkedin.com/in/rishit-singh21)

## License
This project is licensed under the MIT License.

---
Feel free to modify the README to suit any additional features or changes in your project!
