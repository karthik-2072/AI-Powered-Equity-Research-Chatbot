# AI-Powered Equity Research Chatbot

This repository contains an AI-powered chatbot designed to assist with equity research. The chatbot leverages advanced natural language processing (NLP) and machine learning techniques to provide insightful analysis and answers related to equity research.

## Project Overview

The goal of this project is to develop a chatbot that can understand and respond to user queries about equity research. It provides insights into stock performance, market trends, and financial metrics using state-of-the-art NLP models. The chatbot aims to facilitate the process of obtaining financial insights and recommendations.

## Dataset

The chatbot utilizes financial data and market reports from various sources, including:

- **Historical Stock Prices:** Time-series data of stock prices.
- **Financial Statements:** Quarterly and annual reports of companies.
- **Market News:** Latest news articles and financial reports.

## Key Features

- **Natural Language Understanding:** Ability to understand and respond to user queries related to equity research.
- **Stock Performance Analysis:** Provides insights on stock performance, including historical data and trends.
- **Financial Metrics:** Access to key financial metrics and ratios for companies.
- **Market Trends:** Analyzes current market trends based on the latest news and financial reports.

## Model Building

The chatbot employs the following components:

- **Preprocessing:** Data cleaning and transformation for NLP, including tokenization, stemming, and stop-word removal.
- **NLP Models:** Utilizes models like BERT (Bidirectional Encoder Representations from Transformers) or GPT (Generative Pre-trained Transformer) for understanding and generating responses.
- **Machine Learning:** Algorithms for predicting stock performance and trends based on historical data and financial indicators.

## Implementation

The chatbot is implemented using:

- **Python:** The primary programming language for data processing and model building.
- **LangChain:** Framework for developing language model applications.
- **Streamlit:** For creating interactive web applications.
- **Unstructured:** For handling unstructured data.
- **FAISS:** For efficient similarity search and clustering.
- **Flask:** To deploy the chatbot as a web application.

## How to Run

1. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

2. **Set Up Environment:**
   - Configure environment variables and files as needed.

3. **Run the Flask Application:**
    ```bash
    python app.py
    ```

## Dependencies

The project requires the following Python libraries:

- langchain==0.0.284
- python-dotenv==1.0.0
- streamlit==1.22.0
- unstructured==0.9.2
- tiktoken==0.4.0
- faiss-cpu==1.7.4
- libmagic==1.0
- python-magic==0.4.27
- python-magic-bin==0.4.14
- OpenAI==0.28.0

