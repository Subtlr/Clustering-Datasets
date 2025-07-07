# <p align="center">subert_folder</p>
Hello, welcome to the folder full of my attempts on clustering the datasets provided by this repository!

## 1. 🧠 [Banknote Authentication with Gaussian Mixture Modelsb](https://github.com/Subtlr/Clustering-Datasets/blob/master/subert_folder/banknote_sW.ipynb)

This notebook explores unsupervised clustering techniques on the [Banknote Authentication dataset](https://archive.ics.uci.edu/ml/datasets/banknote+authentication).  
The goal was to distinguish between forged and genuine banknotes using statistical features — without using the labels during training.

### 🚀 Project Highlights

- Engineered features like `skewness + kurtosis` and `variance` for better separability
- Benchmarked 2 clustering models, HDBSCAN and GMM
- Gaussian Mixture Models (GMM) achieved the best performance with an NMI of **0.8692**
- Visualized Gaussian ellipses to interpret cluster shapes and confidence (it's in the notebook)

### 🏆 GMM Clustering Results

<p align="center">
  <img src="imgs/correlation_matrix.png" width="36.8%" />
  <img src="imgs/feature_engineered_plot.png" width="50%" />
  <img src="imgs/gmm_versus_truthlabels.png" width="100%" />
</p>

Left to Right, Top to Bottom:
1. Correlation Matrix of the original features,
2. The dataset after feature engineering, lastly
3. The results of the GMM model versus the truth labels.

### 📁 Files

- `subert_folder/banknote_sW.ipynb`: Main notebook with all code, plots, and analysis
- `subert_folder/imgs/`: Folder containing the visualizations used above

### 📊 Metrics

| Model     | NMI Score |
|-----------|-----------|
| HDBSCAN   | 0.58      |
| **GMM**   | **0.869** |
> Built with curiosity, NumPy, and a little bit of chaos.  
> — Subert
