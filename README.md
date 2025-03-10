# Langgraph

## Overview
- This project is used to demonstrate how to use `langgraph` - complex workflow engine & `Model Context Protocol (MCP)` to create Universal API Agents

## Installation
- Langgraph
  ```bash
  mkdir -m777 universal-mcp
  cd universal-mcp
  python3 -m venv .venv
  source .venv/bin/activate

  # Add API Keys for HUGGINGFACEHUB_API_TOKEN or GROQ_API_KEY
  touch .env
  
  pip install -U "langgraph-cli[inmem]"

  # Testing Environment Setup
  python hello.py

  # Running Langgraph
  langgraph dev
  ```

## Tutorial
- [Langgraph Tutorial](https://blog.futuresmart.ai/langgraph-tutorial-for-beginners), [more](https://github.com/langchain-ai/langchain-academy)

## Reference
- [Universal API Engine](https://github.com/esxr/langgraph-mcp),[more](https://medium.com/heurislabs/building-a-universal-assistant-to-connect-with-any-api-89d7c353e524)
- [SQL Agent](https://blog.langchain.dev/data-viz-agent/)
