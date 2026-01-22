# ChatBot-OpenAI

A simple Python chatbot using OpenAI's API (GPT-4o-mini).  
This project demonstrates how to interact with OpenAI models locally via Python.

## Features

- Chat with GPT-4o-mini model
- Environment variable support for API keys (no secrets in code)
- Simple command-line interface

## Prerequisites

- Python 3.10+  
- `pip` package manager  
- OpenAI API key (get it from [OpenAI Dashboard](https://platform.openai.com/account/api-keys))

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/ChatBot-OpenAI.git
cd ChatBot-OpenAI
```

2. Install dependencies:
```bash
pip install openai python-dotenv
```

3. Create a .env file in the project root:
```bash
OPENAI_API_KEY=sk-your-openai-api-key
```

# USAGE
```bash
python ChatBot.py
```

Example:
```bash
You: Hello!
Chatbot: Hi there! How can I help you today?
```

# Security

API keys should never be stored in code.
Always use .env files and python-dotenv to load keys securely.

# License

This project is open-source and available under the MIT License.
