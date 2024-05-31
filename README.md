
# QnA Chatbot

## Project Overview
This project aims to build a Q/A chatbot using Retrieval-Augmented Generation (RAG) to answer questions from website FAQs. The project will involve web scraping, data preprocessing, building a chatbot using Streamlit and integrating with AWS Elasticsearch for vector storage and retrieval.

[Documentation](https://codelabs-preview.appspot.com/?file_id=1oubejmErqcJelc14aIIUMIOesVuE9EheAMbUm3RXXPg#1)

[Application Link](https://qna-rag.streamlit.app/)


![Screenshot 2024-05-27 at 4 22 01 PM](https://github.com/INFO-7374-Algorithmic-Digital-Marketing/faq-chat-bot/blob/main/UI.png)

## Architecture Diagram:

![Architecture Diagram](https://github.com/INFO-7374-Algorithmic-Digital-Marketing/faq-chat-bot/blob/main/rag_chatbot_final.drawio.png)

## Goals
- Scrape FAQ pages from selected websites.
- Build a Streamlit app for the chatbot interface.
- Use AWS Elasticsearch for storing and retrieving vector data.
- Evaluate the chatbot's performance using AWS Bedrock.

## Setup Instructions
# Clone the repository
git clone https://github.com/deveshcode/QnA_Chatbot.git
cd QnA_Chatbot

# Create and activate a new Conda environment
conda create --name qna_chatbot_env python=3.9 -y
conda activate qna_chatbot_env

# Install the required packages
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app2.py
