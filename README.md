
# Kenny the AI Chatbot

Kenny is a Python-based AI chatbot built using spaCy and NLTK. It is designed to understand and respond to user inputs, with functionality for natural language processing (NLP) and fallback responses when the input is not recognized.

## Features

- Natural language processing with spaCy
- Customizable fallback responses
- Responds to user input based on pattern matching and named entity recognition (NER)
- Built with Python 3.8

## Installation

1. Clone the repository or download the files.
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv chatbot_env
   ```
3. Activate the virtual environment:
   - On Windows:
     ```bash
     chatbot_env\Scriptsctivate
     ```
   - On macOS/Linux:
     ```bash
     source chatbot_env/bin/activate
     ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the chatbot:
   ```bash
   python chatbot.py
   ```
2. Start chatting with Kenny by typing in your inputs.
3. Type `quit` to end the conversation.

## Dependencies

- spacy
- nltk
- torch

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
