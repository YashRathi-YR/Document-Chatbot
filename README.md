# Document-Chatbot
Document Chatbot Using Gemini Pro Model And RAG


# Doctor Document


**Doctor Document** is an advanced AI chatbot built using the Retrieval-Augmented Generation (RAG) framework, leveraging Google's Generative AI model Gemini-PRO. This application processes uploaded PDF documents by breaking them down into manageable chunks, creates a searchable vector store, and generates accurate answers to user queries. This ensures high-quality, contextually relevant responses for an efficient and effective user experience.

## Features

- **Enter Your API Key**: You'll need a Google API key for the chatbot to access Google's Generative AI models. Obtain your API key [here](https://makersuite.google.com/app/apikey).
- **Upload Your Documents**: The system accepts multiple PDF files at once, analyzing the content to provide comprehensive insights.
- **Ask a Question**: After processing the documents, ask any question related to the content of your uploaded documents for a precise answer.

## How It Works

1. **API Key**: Users need to provide a Google API key to utilize the Google Generative AI model.
2. **PDF Upload**: Users can upload multiple PDF files which the application will process and index.
3. **Question & Answer**: Users can ask questions related to the content of the uploaded PDFs, and the chatbot will provide detailed answers using the content from the documents or external knowledge when necessary.

## Installation

To run this application locally, you'll need to install the following Python packages:

```bash
pip install streamlit PyPDF2 langchain langchain_google_genai google-generativeai faiss-cpu
```

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/doctor-document.git
    cd doctor-document
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the application:
    ```bash
    streamlit run app.py
    ```

