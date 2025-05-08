# 🧠 Lithuanian News Clustering & Summarization

## ENGLISH 🇬🇧

This project presents an end-to-end NLP pipeline for Lithuanian news summarization and clustering. It includes data collection from major Lithuanian news portals, abstractive summarization using a fine-tuned mBART model, semantic encoding via SentenceTransformer, and clustering with UMAP and Agglomerative methods.

This project was developed as a final assignment for the CodeAcademy data science bootcamp and serves as a showcase in the professional portfolio.

## LIETUVIŲ 🇱🇹

Šis projektas pateikia pilną NLP sprendimą lietuviškų naujienų santraukų generavimui ir temų grupavimui. Įtrauktas duomenų surinkimas iš pagrindinių naujienų portalų, santraukų generavimas naudojant išmokytą mBART modelį, semantinis kodavimas ir klasterizavimas naudojant UMAP bei Agglomerative metodą.

Projektas sukurtas kaip CodeAcademy baigiamasis darbas ir naudojamas profesiniame portfolio.

## Structure

- `scraper.ipynb` – data collection & cleaning
- `mbart_finetuning.ipynb` – training the summarization model
- `embeddings_generation.ipynb` – sentence embeddings
- `agglomerative_clustering.ipynb` – semantic clustering
- `kmeans_clustering.ipynb` – benchmark clustering

