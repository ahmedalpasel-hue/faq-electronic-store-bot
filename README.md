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
- <img width="1909" height="853" alt="image" src="https://github.com/user-attachments/assets/eeaaab0e-ddb7-4fc0-a243-7866acd77b88" />




<img width="1909" height="599" alt="image" src="https://github.com/user-attachments/assets/603ea06a-d042-4797-ae18-b9254e51f4c8" />



   

  <img width="1919" height="857" alt="image" src="https://github.com/user-attachments/assets/dfd684b6-905d-4b23-869f-b285c8fe4155" />

