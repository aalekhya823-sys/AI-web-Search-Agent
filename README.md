# AI Web Search Agent

## Project Overview

The AI Web Search Agent is an AI-powered application developed using Hugging Face smolagents and Google's Gemini Flash model.

The agent understands user instructions, searches the web using DuckDuckGo, processes the retrieved information, and generates summarized responses.

## Technologies Used

* Python
* Hugging Face smolagents
* Google Gemini Flash
* DuckDuckGo Search
* OpenAI-compatible API interface
* Google Colab

## Key Features

* AI-powered web searching.
* Automated information retrieval.
* Summarization of search results.
* Tool integration using DuckDuckGo.
* LLM integration using Gemini Flash.

## How It Works

1. The user provides a question or instruction.
2. Gemini Flash interprets the user's request.
3. The smolagents framework manages the agent's execution.
4. DuckDuckGo searches for relevant information.
5. The agent processes the retrieved results.
6. Gemini generates a summarized response.

## Project Architecture

User Query → Hugging Face smolagents → Gemini Flash → DuckDuckGo Search → Search Results → Final Answer

## Installation

Install the required libraries:

```bash
pip install -r requirements.txt
```

## API Configuration

Create a Gemini API key using Google AI Studio.

Set the API key as an environment variable:

```python
import os
os.environ["GEMINI_API_KEY"] = "YOUR_API_KEY"
```

For security, never upload your actual API key to GitHub.

## Run the Project

Open the `AI_Web_Search_Agent.ipynb` notebook in Google Colab.

Configure your Gemini API key and execute the notebook cells.

## Example Task

"Search for five important developments in Artificial Intelligence and summarize them."

## Learning Outcomes

* Understanding AI agents.
* Working with Hugging Face smolagents.
* Integrating external LLM APIs.
* Using search tools in AI applications.
* Understanding tool calling and agent execution.

## Author

Data Science Fresher | Generative AI and Machine Learning Enthusiast
