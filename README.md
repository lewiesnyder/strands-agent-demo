# Strands Agent Demo
A simple demo of the [Strands Agent framework](https://aws.amazon.com/blogs/opensource/introducing-strands-agents-an-open-source-ai-agents-sdk/) to create a simple SQL agent

## Requirements
- Make sure you have python 3.11 or higher
- [UV](https://docs.astral.sh/uv/) for dependency management
- [docker](https://www.docker.com/) to run the [MCP server](https://github.com/lewiesnyder/mcp-experiment)
- [ollama](https://ollama.com/) to run the model
    - [llama3.2](https://ollama.com/library/llama3.2) for inference
- or 

## Installation
- create and activeate the virtual env: `uv venv && source .venv/bin/activate`
- install the dependencies: `uv sync`
- get the sql agent [MCP server](https://github.com/lewiesnyder/mcp-experiment)
    - clone the sql agent [repo](https://github.com/lewiesnyder/mcp-experiment) 
    - build the docker image: ` docker build --rm -t mcp-experiment .`
- run the [workbook.ipynb](workbook.ipynb)
