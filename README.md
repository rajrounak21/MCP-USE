# MCP-USE 🤖

A powerful CLI-based AI assistant using Langchain, Groq LLM, and Multi-Command Protocol (MCP) to interact with the web, search engines, crypto markets, and travel data — all with conversational memory.

## 🚀 Features

- 🧠 Conversational memory
- ⚡ Groq LLM (Qwen 32B)
- 🌐 Headless web browsing via Playwright
- 🔍 DuckDuckGo search
- 🏡 Airbnb data access
- 💰 Live crypto prices

## 📂 Structure

- `app.py` – Main interactive chat loop  
- `mcp_use.py` – MCPClient & MCPAgent logic  
- `browser_mcp.json` – Plugin definitions  
- `.env` – Store `GROQ_API_KEY` (not included)

## 📦 Install

```bash
pip install langchain langchain_groq python-dotenv


Also install Node.js and make sure npx is available:
npx
node.js


# Clone repo
git clone https://github.com/your-username/MCP-USE.git
cd MCP-USE

# Set your Groq API key
echo "GROQ_API_KEY=your_groq_key" > .env

# Run the assistant
python app.py
