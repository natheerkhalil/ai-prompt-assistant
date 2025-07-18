# AI Prompt Assistant

A simple command-line tool that sends user prompts to OpenAI's GPT-3.5 API and returns the AI's response.

## Features

- Interactive command-line prompt
- Uses OpenAI GPT-3.5 (via `openai` Python SDK)
- API key securely managed via `.env` file

## Setup

### 1. Clone the Repository

```
git clone <repo-url>
cd ai_prompt_assistant
```

### 2. Install dependencies
```pip install -r requirements.txt```

### 3. Create a .env file
Create a file named .env and add your OpenAI API key:
```
OPENAI_API_KEY=your_openai_api_key_here
```

### 4. Run the application
```python main.py```

## Usage
Type a message at the prompt and get a response from GPT-3.5. Type ```exit``` t quit.
```
You: what's the capital of France?
AI: The capital of France is Paris
```
