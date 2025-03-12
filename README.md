# Context-Aware Conversational Search System

A lightweight conversational search engine that maintains context and leverages SBERT embeddings for semantic search. This system is primarily trained on a customer support dataset, enabling it to understand and handle support-related queries.

## Features

- **Context-Aware Search:** Retains conversation context for improved query handling.
- **Intent Recognition:** Uses SBERT embeddings to classify query intents.
- **Knowledge Graph Enrichment:** Retrieves additional info via DBpedia Spotlight.
- **Recommendation System:** Suggests related responses using SBERT-based cosine similarity.

## Technologies

- Python 3.x  
- SBERT (all-mpnet-base-v2)  
- Gradio  
- Pandas, Requests, tensorflow, torch

## Directory Structure

Context-Aware-Conversational-Search-System/ 
   ├── data/ # Customer support dataset files 
   ├── docs/ # Documentation 
   ├── models/ # Saved models  
   ├── notebooks/ # Jupyter notebooks for experiments ├
   ├── requirements.txt 
   └── README.md



## Installation & Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Tekleab15/Context-Aware-Conversational-Search-System.git
   cd Context-Aware-Conversational-Search-System

2. pip install -r requirements.txt
