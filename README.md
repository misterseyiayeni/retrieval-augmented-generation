## Retrieval-Augmented Generation (RAG) Application

This project implements a Retrieval-Augmented Generation (RAG) pipeline using LangChain, NVIDIA AI Endpoints, and FAISS. The RAG system retrieves relevant documents from a vector store and generates context-aware responses using a large language model (LLM). The application is deployed as a FastAPI server and integrated with a Gradio frontend for interactive use.

### Features

- Document Retrieval: Uses FAISS for efficient similarity search to retrieve relevant documents.
- Context-Aware Generation: Leverages NVIDIA's LLM (e.g., LLaMA) to generate responses based on retrieved documents.
- API Deployment: Exposes the RAG pipeline as RESTful APIs using FastAPI and LangServe.
- Interactive Frontend: Provides a user-friendly Gradio interface for testing the RAG system.

### Technologies Used

- LangChain: Framework for building and chaining components in the RAG pipeline.
- NVIDIA AI Endpoints: Provides access to state-of-the-art LLMs for text generation.
- FAISS: Library for efficient similarity search and retrieval of documents.
- FastAPI: Modern web framework for building APIs.
- Gradio: Library for creating interactive web interfaces.
- NVIDIA Embeddings: Used for generating document embeddings.

## Project Structure

<pre style="text-align: left;">
├── server_app.py              # FastAPI server implementation
├── 08_evaluation.ipynb        # RAG pipeline implementation
├── docstore_index/            # Directory containing the FAISS document store
├── requirements.txt           # Python dependencies
├── README.md                  # Project documentation
└── frontend/                  # Gradio frontend code
</pre>

- Basic reasoning
![Basic](https://github.com/user-attachments/assets/7eed84cc-66f1-49a8-9c13-aa65c5e50192)


- RAG
![RAG](https://github.com/user-attachments/assets/7cf67b53-fe20-487e-8cc9-117c8b9ee761)

- RAG evaluation techniques incorporating LLM-as-a-Judge metrics!

![1](https://github.com/user-attachments/assets/fd1c1eb6-0e1f-44c5-a02b-89fced0fcea1)

![2](https://github.com/user-attachments/assets/3d163db0-59ae-45d3-8f60-5191f94b2927)

![3](https://github.com/user-attachments/assets/6533f93d-dcbc-4539-b19e-93acd0dcb544)

![4](https://github.com/user-attachments/assets/239943c9-7bf0-40f6-afa5-0707abb52530)

![5](https://github.com/user-attachments/assets/430f78da-b657-4a25-9bc6-4cebef2e3a82)










  


