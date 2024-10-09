
# CSV_Chatbot using Groq (llama-3.1)

A CSV chatbot using Groq and Llama-3.1 allows users to interact with CSV data through natural language queries, leveraging Groq's acceleration for fast, efficient processing. It enables tasks like filtering, summarizing, and analyzing large datasets in real time, ideal for applications like financial analysis and reporting.

### Steps for create the chatbot using Groq API and Streamlit :

## Step 1:

### Install the nesasary Packages:

```bash
  pip install -r requirements.txt
```

## Step 2:

### import nesasary Packages:
* streamlit
* FAISS
* langchain
* CSVLoader
* tempfile

## Step 3:

### Load the model:
by using the Groq platform to import the API key and call the LLAMA 3.1 model for read the CSV File

## Step 4:

### using FAISS:
using the FAISS HuggingFaceEmbeddings to convert the CSV to chunks and store it to 'vectorstore/db_faiss' 

## Step 5:

### Streamit app:

streamit to create the interface of the chatbot and call the llama llm to chat with the CSV_file

```bash
  streamlit run app.py
```