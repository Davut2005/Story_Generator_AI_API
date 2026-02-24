#  AI Story Generator App

### The idea of the project

Backend Story Generator App is asking some questions about the story the user wants to generate and is generating stories based on the answers. It integrates the OpenAI LLM with openai key. I've developed the api, Prompt and genration logics inside the project.


### Tech Stack

Python, FastAPI, OpenAI, SQLite, SQLAlchemy, uvicorn, uv

### All the project requirements and libraries are in pyproject.toml file

### Build the backend server in the terminal

1. Install all dependencies
uv sync

2. Run the servera
uv run uvicorn main:app --reload