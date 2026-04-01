## 📘 Notebooks Overview

- **1_Advanced_RAG_and_Retrieval.ipynb**  
  Introduces advanced retrieval techniques beyond naïve RAG by combining sparse (BM25) and dense (SBERT) methods. Implements Hybrid Retrieval with Reciprocal Rank Fusion (RRF) and explores how different retrieval strategies capture lexical vs semantic relevance.

- **2_Reranking_and_Query_Expansion.ipynb**  
  Improves retrieval precision using cross-encoder re-ranking (`ms-marco-MiniLM`) to better score query-document pairs. Also implements query expansion techniques like HyDE and multi-query generation to bridge the gap between user queries and technical document language.

- **3_Generation_Enhancement.ipynb**  
  Focuses on optimizing the generation stage of RAG by refining prompts, structuring retrieved context, and improving answer coherence. Explores strategies to reduce hallucinations and ensure responses are grounded in retrieved documents.

- **Unit3_Assignment.ipynb**  
  Integrates all components into a full production-style Advanced RAG pipeline: query expansion → hybrid retrieval → re-ranking → LLM generation. Includes experimental comparison with naïve RAG to demonstrate performance improvements. :contentReference[oaicite:0]{index=0}
