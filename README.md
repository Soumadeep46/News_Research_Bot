# News_Research_Bot
This a user-friendly news research tool designed for effortless information retrieval. Users can input article URLs and ask questions to receive relevant insights from the stock market and financial domain.

## Features

- Load URLs or upload text files containing URLs to fetch article content.
- Process article content through LangChain's UnstructuredURL Loader
- Construct an embedding vector using OpenAI's embeddings and leverage FAISS, a powerful similarity search library, to enable swift and effective retrieval of relevant information
- Interact with the LLM's (Chatgpt) by inputting queries and receiving answers along with source URLs.

## Working
![Untitled design](https://github.com/user-attachments/assets/c09a33bb-629e-46e2-a70c-237c59748fb0)

## Installation

1.Clone this repository to your local machine using:

```bash
  git clone https://github.com/Soumadeep46/News_Research_Bot
```
2.Navigate to the project directory:

```bash
  cd News_Research_Bot
```
3. Install the required dependencies using pip:

```bash
  pip install -r requirements.txt
```
4.Set up your OpenAI API key by creating a .env file in the project root and adding your API

```bash
  OPENAI_API_KEY=your_api_key_here
```
## Usage/Examples

1. Run the Streamlit app by executing:
```bash
streamlit run main.py

```
