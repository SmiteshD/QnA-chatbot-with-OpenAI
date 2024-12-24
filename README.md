# Enhanced Q&A Chatbot with OpenAI

This project is a user-friendly Q&A chatbot powered by OpenAI's GPT models, developed using **Streamlit** and **LangChain**. The chatbot allows users to ask questions and receive AI-generated responses with adjustable settings for the language model and response behavior.

## Features

- **Customizable Settings**:
  - Select from multiple OpenAI GPT models (`gpt-4o`, `gpt-4-turbo`, `gpt-4`).
  - Adjust the temperature for creative or deterministic responses.
  - Configure the maximum number of tokens for responses.

- **Streamlit-based Interface**:
  - Intuitive UI for seamless user interaction.
  - Sidebar settings to personalize the chatbot's behavior.

- **LangChain Integration**:
  - Modular prompt templates for dynamic query handling.
  - Tracking and management through LangChain APIs.

## Prerequisites

- Python 3.10
- OpenAI API Key
- LangChain API Key (optional, for advanced tracking)

## Installation

**Clone the repository:**
   ```bash
   git clone https://github.com/your-username/qna-chatbot.git
   cd qna-chatbot
```

**Install the required dependencies:**
```bash
pip install -r requirements.txt
```

**Set up environment variables by creating a .env file:**
```bash
OPENAI_API_KEY=your_openai_api_key
LANGCHAIN_API_KEY=your_langchain_api_key
```

## Usage
1.Run the Streamlit application:
  ```bash
  streamlit run app.py
```

2.Open the local Streamlit server in your browser (usually at http://localhost:8501).

3.Enter your OpenAI API Key in the sidebar and configure settings like model, temperature, and max tokens.

4.Input your question in the main text field and receive an AI-generated response.

Project Structure
app.py: Main application file.
requirements.txt: Contains all the dependencies.
.env: Environment variables (not included in the repository, needs to be created).

## License
- This project is licensed under the MIT License. Feel free to use, modify, and distribute it.
