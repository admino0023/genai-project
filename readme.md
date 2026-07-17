# ESP32 Datasheet RAG Chatbot

## Overview

The ESP32 Datasheet RAG Chatbot is a Retrieval-Augmented Generation (RAG) application that allows users to ask questions about the ESP32 datasheet in natural language. The chatbot retrieves the most relevant information from the datasheet using semantic search and provides accurate responses based on the document.

## Features

* Load and process the ESP32 datasheet (PDF)
* Split the document into manageable text chunks
* Generate embeddings using Sentence Transformers
* Store embeddings in a FAISS vector database
* Perform semantic similarity search
* Retrieve relevant datasheet content for user queries
* Easy to extend with LLMs such as Gemini, OpenAI, or Ollama

## Technologies Used

* Python
* LangChain
* FAISS
* Hugging Face Sentence Transformers
* PyPDF
* VS Code

## Project Structure

```text
ESP32-RAG-Chatbot/
│
├── esp32_datasheet_en.pdf
├── app.py
├── requirements.txt
├── faiss_index/
├── README.md
└── myenv/
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/ESP32-RAG-Chatbot.git
```

2. Navigate to the project folder:

```bash
cd ESP32-RAG-Chatbot
```

3. Create a virtual environment:

```bash
python -m venv myenv
```

4. Activate the virtual environment:

**Windows**

```bash
myenv\Scripts\activate
```

5. Install the required packages:

```bash
pip install -r requirements.txt
```

## Usage

Run the application:

```bash
python app.py
```

Example query:

```text
What is the maximum CPU frequency of the ESP32?
```

The chatbot retrieves the most relevant sections from the ESP32 datasheet using FAISS similarity search.

## How It Works

1. Load the ESP32 datasheet PDF.
2. Split the document into text chunks.
3. Generate vector embeddings.
4. Store embeddings in a FAISS vector database.
5. Retrieve the most relevant chunks based on the user's question.
6. Return the retrieved information (or pass it to an LLM for answer generation).

## Future Improvements

* Integrate Gemini or OpenAI for answer generation
* Add a Streamlit web interface
* Support multiple PDF documents
* Implement conversational memory
* Deploy the application on the cloud

## Requirements

* Python 3.10+
* LangChain
* langchain-community
* langchain-huggingface
* langchain-text-splitters
* sentence-transformers
* faiss-cpu
* pypdf

## Author

**Aditya Jadhav**

## License

This project is intended for educational and learning purposes.
