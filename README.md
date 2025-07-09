### README

This project uses unsupervised machine learning to cluster mushroom specimens and identify features correlated with edibility. The dataset (cited below) includes categorical features such as cap shape, cap surface, cap color, bruises, odor, and more. Each row represents a single mushroom, labeled as either edible or poisonous. While the target variable is not used during clustering, it serves to evaluate how well the discovered clusters correspond to true edibility classes. Additionally, supervised learning via Logistic Regression is applied to predict mushroom edibility using labeled data. By comparing the performance and interpretability of both approaches, the project aims to highlight their respective strengths and limitations in analyzing categorical biological data.

The primary models used in this project are Logistic Regression for supervised classification and K-Modes for unsupervised clustering.

This data set was retrieved from the UCI Machine Learning Database and contains  descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family, which are identified as either edible or poisonous.

Citation:
Mushroom [Dataset]. (1981). UCI Machine Learning Repository. https://doi.org/10.24432/C5959T.
