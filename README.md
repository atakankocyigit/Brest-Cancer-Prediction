# Brest-Cancer-Prediction

The model was created using a knn machine learning algorithm using the Brest cancer data set. The data set used in the project is https://www.kaggle.com/uciml/breast-cancer-wisconsin-data. The results were compared by applying the tune process. Then, a comparison was made using two different methods, Principal component analysis (PCA) and Neighborhood components analysis (NCA), to reduce the parameters. Thus, a comparison was made in 4 different ways in the project.

The following libraries must be installed in order to run the project.

- import numpy as np
- import pandas as pd
- import seaborn as sns
- import matplotlib.pyplot as plt
- from matplotlib.colors import ListedColormap
- from sklearn.preprocessing import StandardScaler
- from sklearn.model_selection import train_test_split, GridSearchCV, StratifiedKFold, cross_val_score
- from sklearn.metrics import accuracy_score, confusion_matrix
- from sklearn.neighbors import KNeighborsClassifier, NeighborhoodComponentsAnalysis, LocalOutlierFactor
- from sklearn.decomposition import PCA
- from sklearn.metrics import plot_confusion_matrix
- from sklearn.metrics import confusion_matrix
- import warnings

## LICENSE
MIT LICENSE
