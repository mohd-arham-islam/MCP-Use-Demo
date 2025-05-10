# MCP Chatbot with Groq and UV

This project runs a chatbot powered by Groq and MCP, with browser automation capabilities.

## Setup

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/mcp-chatbot.git
   cd mcp-chatbot
   ```

2. **Install dependencies using uv**  
   ```bash
   uv venv
   uv pip install -r requirements.txt
   ```

3. **Create a `.env` file**  
   Add your Groq API key:
   ```
   GROQ_API_KEY=your_groq_api_key_here
   ```

4. **Ensure `mcp.json` is present in the project directory**

## Run the chatbot

```bash
uv pip install .
python app.py
```

Type your messages in the terminal. Use `exit` or `quit` to end, and `clear` to reset the conversation memory.
