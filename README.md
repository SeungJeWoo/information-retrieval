# Information Retrieval System for Question Answering
A transformer-based information retrieval system for extracting relevant context from large-sized documents in a vector database to enhance question answering capabilities with LLMs

**Abstract:**  
Recent advancements in large language models (LLMs) have greatly enhanced automated answer generation systems. However, extracting the most relevant context from diverse documents—such as financial reports, legal submissions, training materials, and annual reports—remains challenging. In this work, we design and implement a retrieval system on a local instance that leverages vector-based search using Milvus to efficiently match embeddings generated from document texts and user queries. We describe our design decisions, including our choice of transformer models (e.g., BERT, MiniLM, MPNet, and Longformer), as well as our data preprocessing, embedding generation, and search techniques. Experimental evaluations highlight the trade-offs involved and demonstrate that proper tuning can significantly improve context narrowing for automated answer generation.

