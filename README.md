# AI_chatbot-
An AI-powered chatbot built with Streamlit, LlamaIndex, Gemini, and Pinecone that answers questions about the Indian Constitution.

#1.Indian Constitution Chatbot
#2.Description

This is an AI-powered chatbot built using LlamaIndex, Gemini, and Pinecone.
It allows users to ask questions related to the Indian Constitution, and the chatbot responds with accurate answers based on the uploaded data.
The app is built using Streamlit for an interactive web interface.

#3.Features

Answers queries about the Indian Constitution

Uses Gemini for language understanding and embeddings

Utilizes Pinecone as a vector database for document retrieval

Built with Streamlit for a simple web UI

#4.Project Structure
indian-constitution-chatbot/
│
├── data/
│   └── constitution.pdf
│
├── app.py
├── README.md
├── requirements.txt

#5.Setup Instructions
1. Clone the repository
git clone https://github.com/your-username/indian-constitution-chatbot.git
cd indian-constitution-chatbot

2. Install dependencies
pip install -r requirements.txt

3. Set up your API keys

Create a .env file or set environment variables directly in your code or terminal:

GOOGLE_API_KEY=your_google_api_key
PINECONE_API_KEY=your_pinecone_api_key

4. Add your data

Place your Indian Constitution PDF inside the data/ folder.

5. Run the app
streamlit run app.py

#6.Example Usage

Once the app is running, open the Streamlit interface in your browser.
Type a question like:

What is Article 370 of the Indian Constitution?

The chatbot will respond with a relevant answer based on the document.

#7.Technologies Used

Python

Streamlit

LlamaIndex

Gemini API

Pinecone
