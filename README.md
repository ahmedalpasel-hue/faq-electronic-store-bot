# faq-electronic-store-bot
An intelligent FAQ bot for an electronics store using Python, FAISS, and Streamlit. It retrieves product and policy information, performs sentiment analysis, and provides a user-friendly web interface

## Overview
An intelligent FAQ bot for an electronics store.  
It answers customer questions about store policies, products, and services using:
- Knowledge base (`store_data.py`)
- EfficientRetriever (embeddings + FAISS)
- Sentiment analysis
- Streamlit web interface

## Features
- Smart retrieval of store policies and product details
- Sentiment analysis of customer queries
- Interactive web interface with Streamlit
- Modular and extensible code structure


## How to Run
1. Install requirements:
   ```bash
   pip install -r requirements.txt
2. Run the FAQ bot in console:
    python faq_bot.py
   
4. Launch the web interface:
   streamlit run faq_ui.py

Example Questions:
- Do you offer free shipping?
- Tell me about Laptop A
- I’m very upset with Product B!
- Excellent quality, I love Smartphone Z!

Screenshots:
   
  -<img width="1919" height="880" alt="Screenshot 2026-01-08 155053" src="https://github.com/user-attachments/assets/14894fb3-1448-4891-806e-c2b237bb2193" />
