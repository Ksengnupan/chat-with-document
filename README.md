# Chat with Document

This project allows you to chat with a PDF document using Retrieval Augmented Generation (RAG) and Chroma as a vector database, with a Streamlit UI.

## Features

- Upload a PDF document and chat with it.
- Uses LangChain for managing the conversation and retrieval.
- Embeds documents using Ollama embeddings.
- Stores and retrieves document vectors using Chroma.
- Streamlit-based user interface.

## Requirements

- Python 3.8+
- See [requirements.txt](requirements.txt) for a list of dependencies.

## Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv .venv
    source .venv/Scripts/activate # On Windows
    ```

3. Install the dependencies:
    ```sh
    pip install -r requirements.txt
    ```

4. Create a `.env` file with the following content:
    ```env
    URL = "your model host point"
    MODEL = "your model name"
    ```

## Usage

1. Run the Streamlit app:
    ```sh
    streamlit run app.py
    ```

2. Open your web browser and go to `http://localhost:8501`.

3. Upload a PDF file and start chatting with it.
