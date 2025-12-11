# K-Means Clustering Tutorial: Choosing the Optimal Number of Clusters

This repository contains all materials for my machine learning tutorial on "selecting the optimal number of clusters (K)" in K-Means using the "Elbow Method" and "Silhouette Score".  
This work was completed as part of the *Machine Learning and Neural Networks* module.

---

#Tutorial PDF  
The full written tutorial (PDF) explaining theory, visuals, and interpretation is located in this repository.

This tutorial covers:

- How K-Means clustering works  
- Why choosing K matters  
- Elbow Method (Inertia)  
- Silhouette Score  
- Visual comparison of clustering results for K = 2, 3, 4, 5  
- Practical guidelines for cluster selection  
- Ethical & accessibility considerations in ML  
- References to scientific papers  

---

# Jupyter Notebook  

The complete code used to generate all plots and metrics is provided in:

- **ML code.ipynb**

The notebook includes:

- Dataset generation using `sklearn.datasets.make_blobs`
- Preprocessing using `StandardScaler`
- Inertia & Silhouette score computation for K = 2 to 10  
- Elbow plot  
- Silhouette plot  
- Cluster plots for K = 2, 3, 4, 5  
- Summary table of metrics  
- Export of figures used in the report  

The notebook is fully executable and requires no modifications.

---

## Figures  

All images used in the tutorial (plots) are available in this repository as `.png` files.  
These include:

- Raw dataset visualisation  
- Elbow plot  
- Silhouette plot  
- Cluster visualisations for K = 2, 3, 4, and 5  

---

# Requirements

To run the notebook, install:

```bash
pip install numpy matplotlib scikit-learn pandas
```

or using conda:

```bash
conda install numpy matplotlib scikit-learn pandas
```

Python version: **3.8+**

---

# How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/riya-bhatta092/k-means-tutorial
   ```

2. Open the notebook:
   ```bash
   jupyter notebook "ML code.ipynb"
   ```

3. Run all cells to reproduce:
   - Elbow plot  
   - Silhouette plot  
   - Cluster visualisations  
   - Summary metrics  

---

# Academic Context

This tutorial was created for the following module:

- **Course:** Machine Learning and Neural Networks  
- **Instructor:** Peter Scicluna  
- **Institution:** University of Hertfordshire  
- **Assessment Weight:** 40%  

---

## License

This project is released under the **MIT License**.  
See the `LICENSE` file for complete terms.

---

## Contact

**Author:** Riya Bhatta 
**GitHub:** https://github.com/riya-bhatta092
