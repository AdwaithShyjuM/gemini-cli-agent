# Gemini CLI Agent

A command-line AI assistant built with Python, LangGraph, and Google's Gemini model.

## Setup Instructions

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/your-username/gemini-cli-agent.git](https://github.com/your-username/gemini-cli-agent.git)
    cd gemini-cli-agent
    ```

2.  **Install Dependencies**
    This project uses `uv` for package management. This command creates a virtual environment and installs all packages from the `uv.lock` file.
    ```bash
    uv sync
    ```

3.  **Add API Key**
    Create a new file named `.env` and add your Google API key inside it:
    ```env
    GOOGLE_API_KEY="YOUR_API_KEY_HERE"
    ```

## How to Run

1.  **Activate the Virtual Environment**
    ```bash
    source .venv/bin/activate
    # On Windows use: .venv\Scripts\activate
    ```

2.  **Run the Script**
    ```bash
    python main.py
    ```