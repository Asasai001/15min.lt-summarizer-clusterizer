# Methodology

## 1. Data Collection & Cleaning

- Sources: Lithuanian news portals (e.g., 15min.lt)
- Text preprocessing: lowercase, lemmatization, stop word removal
- Fields: title, content, GPT-generated summaries

## 2. Summarization (mBART fine-tuning)

- Facebook mBART model used for multilingual summarization
- Cascaded Training:
  - Phase 1: decoder-only training
  - Phase 2: encoder-only training
  - Phase 3: joint training
  - Phase 4: LoRA fine-tuning
  - Phase 5: LoRA fine-tuning with longer inputs

## 3. Embeddings

- SentenceTransformer with `paraphrase-multilingual-MiniLM-L12-v2`
- Encoded both cleaned article and model-generated summaries
- Normalized embeddings for clustering

## 4. Clustering

- Agglomerative Clustering with cosine affinity
- UMAP visualization (n_neighbors=25, min_dist=0.3)
- Cluster naming based on top TF-IDF words and article titles
- KMeans + TF-IDF baseline as benchmark

