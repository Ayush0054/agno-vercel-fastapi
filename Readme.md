# AgentOS FastAPI Application

A FastAPI application powered by AgentOS that provides an AI assistant service using OpenAI's GPT models.

## Overview

This project creates an AI assistant using the AgentOS framework, which provides a structured way to build and deploy AI agents. The assistant is configured with GPT-5-mini and serves responses through a FastAPI web application.

## Features

- 🤖 AI Assistant powered by OpenAI GPT-5-mini
- 🚀 FastAPI web framework for high performance
- 📝 Markdown support for rich text responses
- 🔄 Hot reload for development
- 🌐 AgentOS integration for agent management

## Prerequisites

- Python 3.8+
- OpenAI API key

## Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd agno-vercel-fastapi
```

2. Create and activate a virtual environment:
```bash
python -m venv agnoenv
source agnoenv/bin/activate  # On Windows: agnoenv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up your OpenAI API key:
```bash
export OPENAI_API_KEY="your-api-key-here"
```

## Usage

### Development Server

Run the development server with hot reload:

```bash
python server.py
```

The application will be available at `http://localhost:7777`

### Production Deployment

For production deployment, you can use uvicorn directly:

```bash
uvicorn server:app --host 0.0.0.0 --port 7777
```

## Project Structure

```
agno-vercel-fastapi/
├── server.py              # Main application file
├── requirements.txt       # Python dependencies
├── agnoenv/              # Virtual environment
└── Readme.md             # This file
```

## Configuration

The assistant is configured in `
