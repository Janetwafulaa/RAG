#  Constitution of Kenya RAG System  

This project implements a **Retrieval-Augmented Generation (RAG)** pipeline that allows you to query the **Constitution of Kenya (2010)** in natural language. The system retrieves relevant sections from the Constitution (in PDF format) and uses an LLM to generate clear, contextual answers with references to the original text.  

---

##  Project Overview  
- **Data Source**: Constitution of Kenya, 2010 (PDF).  
- **Embedding & Storage**: Converts the PDF into chunks, generates vector embeddings, and stores them in a ChromaDB vectorstore.  
- **Retrieval**: Uses similarity search to fetch relevant passages from the Constitution.  
- **LLM Integration**: Answers user questions by combining retrieved passages with reasoning from Groq model.  

