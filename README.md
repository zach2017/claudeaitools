# claudeaitools


## Demo Setup MAC OS

- Source Info on MCP Protocol

https://github.com/modelcontextprotocol

## Install UV 

- curl -LsSf https://astral.sh/uv/install.sh | sh

## Create a new directory for our project
uv init weather
cd weather

## Create virtual environment and activate it
uv venv
source .venv/bin/activate

## Install dependencies
uv add "mcp[cli]" httpx

## Create our server file
touch weather.py

- Update Code SEE: weather.py

# Run app 
- uv --directory `pwd` run weather.py

# Future

- Web interface

### LangChain-AI

https://langchain-ai.github.io/langgraph/tutorials/introduction/

### AI Web Search Inteface

https://tavily.com/
