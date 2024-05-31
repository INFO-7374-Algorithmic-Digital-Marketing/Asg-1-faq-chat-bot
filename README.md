
# QnA Chatbot

![Screenshot 2024-05-27 at 4 22 01 PM](https://github.com/deveshcode/QnA_RAG/assets/37287532/7137dcec-66dc-4653-90f8-0fd833e0c5d9)


## Project Overview
This project aims to build a Q/A chatbot using Retrieval-Augmented Generation (RAG) to answer questions from website FAQs. The project will involve web scraping, data preprocessing, building a chatbot using Streamlit, and integrating with AWS Elasticsearch for vector storage and retrieval.

## Goals
- Scrape FAQ pages from selected websites.
- Build a Streamlit app for the chatbot interface.
- Use AWS Elasticsearch for storing and retrieving vector data.
- Evaluate the chatbot's performance using AWS Bedrock.

## Setup Instructions
1. Clone the repository

```bash
git clone https://github.com/deveshcode/QnA_Chatbot.git
cd QnA_Chatbot
```

2. Create and activate a new Conda environment

```bash
conda create --name qna_chatbot_env python=3.9 -y
conda activate qna_chatbot_env
```

3. Install the required packages

```bash
pip install -r requirements.txt
```

4. Run the Streamlit app

```bash
streamlit run app2.py
```

