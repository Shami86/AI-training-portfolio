# Day 1 — Semantic Search & Vector Databases (RAG Foundations)

## Objective
Build a semantic search system from unstructured data using embeddings and a vector database.

The goal was to understand how modern AI systems retrieve information beyond keyword matching.

---

## Use case
A restaurant pizza menu originally available as an image (JPEG).

The challenge was to:
- extract information,
- structure it,
- make it searchable in natural language.

---

## Technical pipeline

Image (JPEG)  
→ OCR  
→ Structured JSON  
→ Embeddings (Sentence Transformers)  
→ Qdrant (Vector Database)  
→ FastAPI (Search API)

---

## Technologies used
- Python
- HuggingFace (sentence-transformers)
- Qdrant (Docker Compose)
- FastAPI & Uvicorn
- Docker
- VS Code / virtual environment

---

## Key concepts learned
- Embeddings and vector representations
- Cosine similarity
- Vector indexing and collections
- Difference between dashboard inspection and real semantic search
- RAG foundations (without LLM reasoning)

---

## Results
- Successfully indexed ~20 menu items in Qdrant
- Verified vectors and payloads in the Qdrant dashboard
- Built an API capable of receiving a text query and returning the most relevant items

---

## Key takeaway
Vector databases are not search engines by themselves.
They must be combined with embedding models and an API layer to enable real semantic search.
