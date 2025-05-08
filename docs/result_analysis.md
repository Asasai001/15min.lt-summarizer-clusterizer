# 📊 Results & Interpretation

## Summary Model (mBART)

- Fine-tuned on 3000+ Lithuanian articles
- Validation ROUGE-L: ~0.48
- Final summaries captured high-level semantics well
- Final summaries used for clustering embeddings

## Agglomerative Clustering

- Chosen clusters: 8 (aligned with real-world topics)
- Silhouette Score: ~0.26 (acceptable for high-dimensional text)
- Davies–Bouldin Index: ~0.84 (indicates good separation)
- Topic clarity: strong (e.g., sports, politics, society)

## KMeans Clustering (TF-IDF baseline)

- Less semantically coherent clusters
- Lower silhouette score and interpretability

## UMAP Visualization

- Well-separated topic clusters
- Cluster labeling with top terms enhanced interpretability

