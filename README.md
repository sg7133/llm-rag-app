Version = 1.1

## Features Implemented


1. Upload single PDF document to a folder and use RAG and vectorstore to ask relevant questions from the document
2. Made the output of the llm cleaner by hiding the RAG context and question being repeated in the llm response



## Backlog
1. add capability to chat with contex
2. add capability to add multiple documents of different formats 
3. Divide the logic into 2 tiers and run client and api separately on local machine
4. Take the 2 tier app and deploy it on a server on a cloud and give access to client
5. Fortify code
    a. check if same PDF is uploaded again to avoid storing in vectorestore
    b. check if the document being uploaded is a pdf


## Infra

1. Langchain for orcehstration
2. Streamlit for UI
3. Local Llama for LLM
4. FAISS for vector store
5. OpenAI for embeddings to store in vector store
6. Recurssive Character Text splitter for chunking


### IMPORTANT
1. Download Ollama to run local Llama
2. Register to OpenAI for API Keys
3. Get Langsmith API key for monitoring