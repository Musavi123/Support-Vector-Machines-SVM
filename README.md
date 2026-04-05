# Support-Vector-Machines(SVM)

The project explores the versatility of SVMs in handling both multivariate regression and non-separable classification problems.

1. Reactive-Ion Plasma Etching (Multivariate Regression) 

Implemented Support Vector Regression (SVR) to predict four critical semiconductor process targets: Etch Rate, Uniformity, Oxide, and Photoresist.

    Methodology: Utilized StandardScaler for feature and target scaling and performed kernel optimization.

    Key Findings: The 'sigmoid' kernel was optimal for most variables, while a 'linear' kernel performed best for Oxide. The Etch Rate model achieved the highest R2 at 0.609.

2. Multi-Font Character Recognition (Classification) 

Developed a Support Vector Classifier (SVC) to recognize characters across various font styles.

    Methodology: Employed an RBF kernel with standardized feature sets.

    Performance: The model demonstrated strong generalization with an R2 of 0.820 and high accuracy on unseen data.

3. Statistical Process Control (Pattern Recognition) 

Applied SVC to identify patterns within process control charts (SPC) to monitor manufacturing quality.

    Performance: Achieved an accuracy of 0.884 and a weighted average F1-score of 0.88.

    Reliability: The model showed exceptional precision for specific classes (e.g., Class 5 achieved a perfect F1-score of 1.0).

## Technical Stack

    Language: Python 

    Libraries: scikit-learn (SVC, SVR, StandardScaler), numpy, pandas 

    Reproducibility: All models use a fixed seed (np.random.seed(42)) for consistent results.

## Conclusions

While SVMs provided robust results for complex classification tasks, comparative analysis indicates that further hyperparameter tuning and feature selection could resolve performance discrepancies observed when compared to Multi-Layer Perceptron (MLP) models.
