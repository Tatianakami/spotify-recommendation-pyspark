# 🎵 Music Matcher: Recomendador de Músicas com PySpark

Este projeto utiliza técnicas de Machine Learning para agrupar músicas por similaridade utilizando a base de dados do Spotify.

## 🚀 Tecnologias Utilizadas
* **PySpark** (Processamento de dados)
* **Scikit-Learn/PCA** (Redução de dimensionalidade)
* **K-Means** (Agrupamento/Clustering)
* **Matplotlib/Plotly** (Visualização)

## 📊 Visualização dos Clusters
Aqui está a representação gráfica de como as músicas foram agrupadas no espaço vetorial:

![Gráfico de Clusters](./clusters_spotify.png)

## 🧠 Como funciona?
O modelo processa características como `acousticness`, `danceability` e `energy`. Através do PCA, reduzimos a complexidade e aplicamos o K-Means para criar 50 grupos distintos de músicas.

---
Projeto desenvolvido durante o curso de Data Science aplicada.
