# AI Chatbot

This project is a simple AI chatbot built using the `langchain_ollama` library, designed to simulate conversations by answering user questions based on the provided conversation context. The chatbot uses the Llama model (`llama3`) to generate responses.

## Features

- Real-time chatbot interaction.
- Maintains conversation context to provide relevant answers based on previous inputs.
- Easy to modify the conversation template and model used.

## Requirements

- Python 3.x
- `langchain_ollama` library
- `langchain_core` library

## Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/ai-chatbot.git
    cd ai-chatbot
    ```

2. Install the required dependencies:

    ```bash
    pip install langchain_ollama langchain_core
    ```

## Usage

1. Run the `main.py` file:

    ```bash
    python main.py
    ```

2. Type your questions and interact with the chatbot. To exit the chat, type `exit`.

## How It Works

- The chatbot utilizes the Llama model (`llama3`) to generate responses to user queries.
- The conversation history is stored in the `context` variable, which helps maintain continuity in the conversation.
- The template defines how the conversation context and the user’s question are structured before being sent to the model for response generation.

## Customization

- **Model**: You can modify the `model` variable in the script to use a different version of the Llama model.
- **Template**: The `template` variable in the script defines how the context and user input are formatted before being passed to the model. You can edit this to suit your application's needs.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
