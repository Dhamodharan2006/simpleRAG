🚀 Simple Retrieval-Augmented Generation (RAG) Chatbot 🤖
🌟 Overview:
This project focuses on building a Retrieval-Augmented Generation (RAG) pipeline that combines a Language Model (LLM) with a Retriever to generate more accurate, current, and domain-specific answers. Instead of relying solely on the model’s built-in knowledge, we use external data sources (like websites and documents) to retrieve relevant information, which enhances the model's responses and reduces hallucinations. 🔍

RAG is particularly useful for creating Domain-Specific LLMs, ensuring responses are accurate and contextually appropriate.

🛠️ Technologies Used:
WebBaseLoader 🌐: Scrapes content from websites.

BeautifulSoup 🍲: Extracts useful data from HTML content.

LangChain 🔗: Manages the flow of text processing, embedding generation, and document retrieval.

Gemini Embeddings 🧠: Creates vector embeddings for the text data.

ChromaDB 📦: Stores and retrieves the embeddings for fast and efficient searches.

Gradio 🎮: Builds an interactive user interface for the chatbot.

🔧 What I Worked On:
I developed the pipeline step-by-step to understand how RAG works. Here’s what I did:

Scraping Data 🌐:

Scraped MCP-related content from 3 websites using WebBaseLoader (powered by BeautifulSoup).

Text Processing ✂️:

Split the scraped text into manageable chunks using LangChain to ensure easy handling.

Embedding Generation 💡:

Created vector embeddings for the chunks using Gemini Embeddings.

Storing Embeddings 🗄️:

Stored the embeddings in ChromaDB for efficient similarity-based retrieval.

Retrieving Information 🔄:

Set up the retriever with LangChain to load, process, and manage the embeddings.

Integrated it with Gemini 1.5 Pro to generate contextual responses based on the retrieved information.

Interactive Chatbot 💬:

Built a simple Gradio UI to make the chatbot interactive and engaging for users.
