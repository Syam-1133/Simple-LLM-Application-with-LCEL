# Simple-LLM-Application-with-LCEL

## Project Overview

This project demonstrates how to build a simple Language Model (LLM) application using LangChain Expression Language (LCEL). The application translates text from English into another language (such as Telugu) using both OpenAI and open-source models (Llama3, Gemma2, Mistral) via Groq.

## Key Features

- **Language Model Integration:** Utilizes both OpenAI and Groq-hosted open-source models for text translation.
- **Prompt Engineering:** Uses prompt templates and output parsers to structure and process LLM responses.
- **LCEL Chaining:** Demonstrates how to chain components (prompt, model, parser) for streamlined LLM workflows.
- **Environment Variables:** API keys are managed securely using environment variables and `python-dotenv`.
- **Notebook Demo:** The included Jupyter notebook (`simplelcel.ipynb`) provides a step-by-step walkthrough of the translation pipeline.

## How It Works

1. **API Key Setup:**  
	The application loads API keys for OpenAI and Groq from environment variables using `python-dotenv`.

2. **Model Selection:**  
	You can choose between OpenAI models or open-source models (like Gemma2) via Groq for translation tasks.

3. **Prompt Templates:**  
	Prompts are dynamically generated to instruct the model to translate text into a target language.

4. **Chaining with LCEL:**  
	Components such as the prompt, model, and output parser are chained together using LCEL for a modular and readable workflow.

5. **Translation Example:**  
	The notebook shows how to translate "Hello how are you?" from English to Telugu, and how to generalize this with prompt templates for any language.

## Requirements

- Python 3.8+
- See `requirements.txt` for all dependencies.

## Running the Notebook

1. Install dependencies:
	```bash
	pip install -r requirements.txt
	```
2. Set your `OPENAI_API_KEY` and `GROQ_API_KEY` in a `.env` file.
3. Open `simplelcel.ipynb` and follow the cells for a guided demo.

## Project Structure

- `server.py` – (Optional) Backend server code (not detailed here).
- `simplelcel.ipynb` – Jupyter notebook with the main LLM translation demo.
- `requirements.txt` – List of required Python packages.

---
