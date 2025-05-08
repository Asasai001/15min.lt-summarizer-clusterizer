# Lithuanian News Clustering & Summarization

## ENGLISH 🇬🇧

This project presents an end-to-end NLP pipeline for Lithuanian news summarization and clustering. It includes data collection from major Lithuanian news portals, abstractive summarization using a fine-tuned mBART model, semantic encoding via SentenceTransformer, and clustering with UMAP and Agglomerative methods.


## LIETUVIŲ 🇱🇹

Šis projektas pateikia pilną NLP sprendimą lietuviškų naujienų santraukų generavimui ir temų grupavimui. Įtrauktas duomenų surinkimas iš pagrindinių naujienų portalų, santraukų generavimas naudojant išmokytą mBART modelį, semantinis kodavimas ir klasterizavimas naudojant UMAP bei Agglomerative metodą.


## Structure

- `scraper.ipynb` – data collection & cleaning
- `mbart_finetuning.ipynb` – training the summarization model
- `embeddings_generation.ipynb` – sentence embeddings
- `agglomerative_clustering.ipynb` – semantic clustering
- `kmeans_clustering.ipynb` – benchmark clustering

## Hugging Face
Final mBART fine tuned model can be found on hugging face Arnold001/mbart-lt-summary-phase5

