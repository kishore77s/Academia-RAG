# Academia RAG

This project is a Retrieval-Augmented Generation (RAG) application built with Streamlit and LangChain, designed for academic document search and question answering.

## Features
- Upload and index academic documents
- Semantic search using vector embeddings
- Conversational Q&A interface
- Powered by Streamlit, LangChain, and Groq API

## Live Demo
The application is deployed and available at:

👉 [https://academia-rag-007.streamlit.app/](https://academia-rag-007.streamlit.app/)

## Getting Started

### Prerequisites
- Python 3.8+
- A Groq API key (for LLM access)

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/kishore77s/Academia-RAG.git
   cd Academia-RAG
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.env` file in the project root and add your Groq API key:
   ```env
   GROQ_API_KEY="your_groq_api_key_here"
   ```

### Running Locally
```bash
streamlit run app.py
```

## Deployment
This app is deployed on Streamlit Community Cloud. You can deploy your own fork by following the [Streamlit deployment guide](https://docs.streamlit.io/streamlit-community-cloud/deploy-your-app).

## License
This project is open source and available under the MIT License.
