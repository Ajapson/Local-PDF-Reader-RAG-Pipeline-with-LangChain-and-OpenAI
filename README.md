This project demonstrates how to build a Retrieval-Augmented Generation (RAG) pipeline using the LangChain framework to read and interpret local documents (PDFs or text files), similar to how ChatGPT answers questions with contextual awareness. 
🔧 How It Works
    Load Documents: Reads local PDFs using PyPDFLoader.

    Split Content: Breaks text into manageable chunks with RecursiveCharacterTextSplitter.

    Generate Embeddings: Converts chunks into vector embeddings using OpenAI.

    Store Vectors: Saves embeddings in a local vector database using ChromaDB.

    Retrieve + Generate Answers: On user query, retrieves relevant chunks and uses OpenAI’s language model to generate accurate, context-aware responses.

This setup enables natural language querying of your own documents—ideal for research papers, business files, or any local text-based data.

Note: I used my admission letter pdf for this project
