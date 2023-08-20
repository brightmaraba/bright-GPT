# bright-GPT

## Introduction

BrightGPT is a Python application that allows users to chat with multiple PDF documents. The user can ask questions in natural language about the PDFs and application will provide the answer. The application is built using the LangChain API and the GPT-3 API.

The application's frontend is built using the Streamlit framework.

## How it works

1. PDF Loading: The app reads multiple PDF documents and extracts their text content.

2. Text Chunking: The extracted text is divided into smaller chunks that can be processed effectively.

3. Language Model: The application utilizes a language model to generate vector representations (embeddings) of the text chunks.

4. Similarity Matching: When you ask a question, the app compares it with the text chunks and identifies the most semantically similar ones.

5. Response Generation: The selected chunks are passed to the language model, which generates a response based on the relevant content of the PDFs.

## Dependencies and Installation

1. Clone the repository.

2. Install the dependencies in the requirements.txt file.

3. Create a .env file in the root directory and add the API keys for the LangChain and GPT-3 APIs.

4. Run the app using the command `streamlit run app.py`.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
