# LangChain Tutorial & Lab 4: Build an Ask
## The Doc App

**How to get answers from documents using embeddings, a vector store, and a question-answering chain**

### App overview
1. The user uploads a document text file, asks a question, provides an OpenAI API key, and clicks "Submit."
2. LangChain processes the two input elements. First, it splits the input document into chunks, creates embedding vectors, and stores them in the embeddings database (i.e., the vector store). Then it applies the user-provided question to the Question Answering chain so that the LLM can answer the question.

Run the app locally
```bash
pip install -r requirements.txt

streamlit run main.py
```