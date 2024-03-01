# OpenAI Assistant for Math and Programming Tutoring

## Description
This project leverages OpenAI's GPT-3.5-turbo to create a personal math and programming tutor. The assistant can answer math questions and provide code-related responses by interpreting and executing code snippets. The project includes a FastAPI backend for handling conversations and interactions with the assistant, and a Streamlit web interface for user interaction.

## Features
- Personal math and programming tutor powered by OpenAI GPT-3.5-turbo.
- Interactive chat interface for asking math questions and receiving programming-related assistance.
- FastAPI backend for handling conversations and interactions with the assistant.
- Streamlit web interface for user-friendly interactions.

## Installation
### Prerequisites
- Python 3.8+
- FastAPI
- OpenAI
- Streamlit

### Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/your_username/your_repository.git
    cd your_repository
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Set up the environment variables:
    - `OPENAI_API_KEY`: Obtain an OpenAI API key and set it in your environment.

## Usage
To use the project, follow these steps:

1. Start the FastAPI server:
    ```bash
    uvicorn main:app --reload
    ```

2. Run the Streamlit app:
    ```bash
    streamlit run streamlit_app.py
    ```

3. Access the interactive chat interface and start a new conversation.

## API Reference
The project exposes the following API endpoints:

- `/start`: Initiates a new conversation with the AI assistant.
- `/chat`: Allows users to send messages and receive responses from the assistant.

## Contributing
Contributions are welcome! Follow these steps to contribute to the project:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/improvement`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/improvement`).
5. Create a new Pull Request.

## Authors and Acknowledgment
This project was created by [Your Name].

## Contact Information
For questions or suggestions, please contact [Your Email Address].

## FAQs
**Q:** How can I customize the responses of the AI assistant?
**A:** You can modify the instructions provided to the assistant in `functions.py` to customize its behavior for math and programming tutoring.
