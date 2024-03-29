
**This repository is replicated from Mehmet for learning purposes, all credits to the original creator.

** The LLM will summarize or answer questions on a set of PDF files that you upload; the backend LLM is OpenAI, using OpenAI or HuggingBear's embeddings and langchain; you would need to provide your own API key to the OpenAI subscription.

**Try the app here in CK Loh's Streamlit website:** [PDF Analyzer on Streamlit Cloud](https://ck-app-multipdf-langchain-openai-6fqjfysu2qvmtll65evopd.streamlit.app/)

# PDF Analyzer App

PDF Analyzer App is a question-answering application that allows users to upload documents (PDF or TXT) and ask questions related to the content of those documents. The app utilizes various retrievers such as similarity search and support vector machines to provide relevant answers.

Adapted from Mehmet

## Features

- Upload PDF or TXT documents
- Choose the type of retriever: Similarity Search or Support Vector Machines
- Generate sample question-answer pairs based on the uploaded documents
- Ask questions related to the content of the uploaded documents
- Get answers from the app using the selected retriever method

