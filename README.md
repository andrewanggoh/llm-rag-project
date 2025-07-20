# LLM Application with Retrieval Augmented Generate (RAG)

- **Skills**: data wrangling, feature engineering, streamlit
- **Tools**: Python, Gemini-AI, Streamlit

This project explores Retrieval-Augmented Generation (RAG) to enhance LLM accuracy by combining its internal knowledge with external data sources. After performing thorough data preparation and embedding processes, I implemented a FAISS index with cosine similarity for efficient information retrieval. The system was then integrated with an LLM (*Note: I use Gemini 2.0 Flash - Free Version for this project*) to demonstrate RAG's capability to generate more accurate, context-aware responses. Finally, I developed an interactive Streamlit application to showcase this pipeline, allowing users to query against the augmented knowledge base and observe the improvements over standalone LLM responses.

- **Streamlit**: [aanggoh-llm-rag.streamlit.app](https://aanggoh-llm-rag.streamlit.app)

What You'll Need to Use Streamlit:

1. Prepare a Gemini 2.0 Flash API key
2. Prepare your data in CSV format or use my processed dataset (`games_top200.csv`) included in my [GitHub](https://github.com/andrewanggoh/llm-rag-project)
