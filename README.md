# SureBot
This is a tool to get Perfect Answers with Zero errors! Just copy paste the article URLs which you trust and ask questions to SureBot! The answers will be based on your trusted sources so they will be 100% correct!

### Functional Deployed Application on Streamlit Cloud

https://mainpy-ckn2aqdwyvr3n4pvep6koz.streamlit.app/

## To use this project
1. Clone this repo.
2. Install required dependencies from requirements.

pip install -r requirements.txt
  
3. Use your API key

## Overview

SureBot is an AI-powered Question-Answering (QA) system designed to provide accurate and user-friendly answers based on input from URL articles. It's built using Python, Streamlit, and a variety of AI and machine learning techniques to ensure high-quality responses. This README provides an overview of the project's features, architecture, and deployment.

## Features

1. **Accuracy**: SureBot utilizes advanced AI models, including OpenAI, to ensure precise and contextually relevant answers to user queries.

2. **User-Friendly Interface**: The application is designed with user-friendliness in mind, making it easy for anyone to input questions and obtain accurate responses.

3. **URL Article Integration**: SureBot can load articles from URLs provided by users, making it versatile and capable of answering questions from a wide range of sources.

4. **Text Splitting**: The system intelligently splits the text from articles into token-sized chunks using recursive text splitters. This ensures that long articles are processed efficiently.

5. **Vector Embeddings**: SureBot uses OpenAI embeddings to create vector representations of the text. This allows for semantic search, ensuring that answers are contextually accurate.

6. **Faiss for Efficient Retrieval**: Faiss, a vector database, is employed for storing vector embeddings and efficiently retrieving answers based on vector similarity.

7. **OpenAI API Integration**: The project leverages the OpenAI API to generate answers based on user queries and the vector embeddings stored in the Faiss database.

8. **Streamlit User Interface**: SureBot's user-friendly interface is built using Streamlit, a Python library for creating web applications. This enables users to interact with the system effortlessly.

9. **Cloud Deployment**: The application is deployed in the cloud, making it accessible to users from anywhere with an internet connection.



## Deployment

SureBot is deployed on the cloud, making it accessible to users worldwide using Streamlit Cloud. It can be accessed via a web browser, allowing users to input questions and receive accurate answers from articles provided through URLs.

---



