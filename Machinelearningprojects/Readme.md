
# Machine Learning Projects
 
A collection of machine learning assignments covering classical algorithms, dimensionality reduction, and ensemble methods — all implemented with **scikit-learn**.  
All notebooks are fully executed with outputs, plots, and results included.
 
---
 
## Projects
 
###  — Anxiety Level Classifier
Binary/multiclass classification on a custom mental health dataset.
 
- Logistic Regression implemented **from scratch** with cost tracking
- Gaussian Naive Bayes as baseline comparison
- Custom synthetic data generation to handle class imbalance (levels 5–10)
- EDA: per-class feature ranking exported to JSON
- Dataset: **Enhanced Anxiety Dataset** (10-class scale)
---
 
### — PCA, K-Means & GMM on Face Images
Unsupervised learning and dimensionality reduction on image data.
 
- PCA applied at multiple dimensions (15, 20, 50, 150, 250, 500) with image reconstruction
- Eigenface visualization and per-component variance analysis
- K-Means clustering evaluated with Elbow method and Silhouette Score
- EM algorithm via Gaussian Mixture Models (GMM) with log-likelihood tracking
- Dataset: **LFW (Labeled Faces in the Wild)**
---
 
### — k-NN, Decision Tree & LDA
Comparison of three classifiers with full bias-variance analysis.
 
- k-NN with k sweep and train/val/test split (60/20/20)
- Decision Tree with max-depth tuning and overfitting region visualization
- Linear Discriminant Analysis (LDA) with discriminant component visualization
- Final model comparison: accuracy, F1, Macro-F1, precision-recall
- Dataset: **CovType (Forest Cover Type)** — UCI
---
 
###— SVM, Random Forest & Gradient Boosting
Ensemble methods and kernel-based classification with hyperparameter tuning.
 
- SVM with Linear and RBF kernels, C-sweep evaluated by test F1
- Random Forest and Gradient Boosting with grid search
- Feature importance analysis across all three models
- Final comparison table: accuracy, F1, confusion matrix
- Dataset: **Bank Marketing** — UCI
---
 
## Stack
 
`Python` · `scikit-learn` · `NumPy` · `Pandas` · `Matplotlib` · `Seaborn` · `SciPy`
