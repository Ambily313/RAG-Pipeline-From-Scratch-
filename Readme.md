# Retrieval-Augmented Activity Recommendation System (GenAI Project)

## Overview
This project demonstrates a **Retrieval-Augmented Generation (RAG) pipeline** that combines a traditional **information retrieval system** with a **Large Language Model (LLM)** for generating personalized activity recommendations.  

- **Step 1:** Retrieve the most relevant document from a custom corpus using **cosine similarity**.  
- **Step 2:** Pass the retrieved context and user query to **LLaMA2 (local deployment)**.  
- **Step 3:** Generate human-like, context-aware recommendations.  

This mini-project showcases **how GenAI can be combined with classical NLP methods** to create intelligent and scalable recommendation systems.

---

## Features

- Built a **text similarity search engine** using cosine similarity on token frequency vectors.  
- Designed an **end-to-end retrieval pipeline**:  
  - Query preprocessing  
  - Vector representation  
  - Document similarity computation  
  - Best-match retrieval  
- Integrated with **LLaMA2 via REST API** for augmentation and natural language recommendations.  
- Demonstrated a **lightweight RAG pipeline** using open-source tools.  

---


