# The Sound of Success Through the Years

## Music Clustering Analysis Using Million Song Dataset

**Research Question**: How have the audio characteristics of successful songs evolved over time, and can we identify distinct 'eras' of popular music based on clustering analysis of audio features?

---

## Project Overview

This project analyzes the **Million Song Dataset (10,000 song subset)** using multiple unsupervised learning techniques to understand how successful songs have evolved over decades. We apply **K-means**, **Hierarchical Clustering**, and **DBSCAN** combined with **PCA** and **t-SNE** dimensionality reduction to discover natural patterns in music.

### Key Research Questions

1. What audio features distinguish successful songs across different decades?
2. Can we identify natural clusters representing musical "eras" or styles?
3. How do success metrics correlate with different audio feature clusters?
4. Has the "sound of success" converged or diverged over time?
5. Are there "breakthrough" songs that don't fit established patterns?

---

## Dataset

**Source**: [Million Song Dataset](http://millionsongdataset.com/)
- **Provider**: Echo Nest (acquired by Spotify) / Columbia University
- **Size**: 10,000 song subset (~2.5GB)
- **Format**: HDF5 files organized by artist
- **Time Period**: Songs spanning 1950s-2010
- **Success Metric**: `song_hotttnesss` (0-1 popularity score from 2011)

Analysis, Results and Findings included in the music_clustering_analysis.ipynb Jupyter notebook
---

## Installation & Usage

### Prerequisites
- Python 3.8+
- Jupyter Notebook or JupyterLab

### Setup

1. **Clone the repository**:
```bash
git clone https://github.com/[your-username]/music-clustering-analysis.git
cd music-clustering-analysis
```

2. **Install dependencies**:
```bash
pip install -r requirements.txt
```

3. **Download the Million Song Dataset subset**:
   - Visit: http://millionsongdataset.com/pages/getting-dataset/#subset
   - Extract to `MillionSongSubset/` folder in project directory
   - Or use your existing dataset

4. **Run the notebook**:
```bash
jupyter notebook music_clustering_analysis.ipynb
```

5. **Execute cells sequentially** from Section 1 to Section 10

### Expected Runtime
- Data loading: ~1-2 minutes
- EDA: ~2-3 minutes
- Clustering (all 3 algorithms): ~5-7 minutes
- t-SNE: ~1-2 minutes
- **Total**: ~15-20 minutes on standard hardware
  
---

## Technologies Used

- **Python 3.8+**
- **Data Processing**: pandas, numpy, h5py
- **Machine Learning**: scikit-learn
- **Visualization**: matplotlib, seaborn
- **Clustering**: KMeans, AgglomerativeClustering, DBSCAN
- **Dimensionality Reduction**: PCA, t-SNE
- **Statistical Testing**: scipy.stats

---

## References

**Dataset**:
- Bertin-Mahieux, T., Ellis, D. P., Whitman, B., & Lamere, P. (2011). *The Million Song Dataset*. Proceedings of the 12th International Society for Music Information Retrieval Conference (ISMIR 2011).

---

## Video Presentation

https://drive.google.com/file/d/1U8Vf0ucPZ1PgPpa5e7Oh-0lw5fZccIkE/view?usp=vids_web


---

---

**Questions or Feedback?** Feel free to open an issue or reach out!

