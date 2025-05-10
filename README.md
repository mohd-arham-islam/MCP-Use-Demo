# MCP Chatbot with Groq and UV

This project runs a chatbot powered by Groq and MCP, with browser automation capabilities.

## Setup

1. **Clone the repository**  
   ```bash
   git clone https://github.com/mohd-arham-islam/MCP-Use-Demo.git
   cd MCP-Use-Demo
   uv pip install .
   ```

2. **Update `.env` file**  
   Add your Groq API key:
   ```
   GROQ_API_KEY="<GROQ_API_KEY>"
   ```
   Replace <GROQ_API_KEY> with your API

3. **Ensure `mcp.json` is present in the project directory**

## Run the chatbot

```bash
uv run app.py
```

Type your messages in the terminal. Use `exit` or `quit` to end, and `clear` to reset the conversation memory.
