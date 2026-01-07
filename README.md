# Music-Genre-Classification
This project focuses on classifying music tracks into genres using audio features extracted from the Free Music Archive (FMA) dataset. Three different machine learning algorithms are implemented and compared to evaluate their performance on the same dataset.

The dataset consists of track metadata, genre information, and audio features extracted using Librosa. After cleaning and merging the datasets, relevant numerical features are selected and standardized before training the models.

The following classification models are used:

K-Nearest Neighbors (KNN)

Random Forest Classifier

Support Vector Machine (SVM)

Each model is trained on the same training data and evaluated using accuracy, precision, recall, F1-score, confusion matrices, and visual comparison plots. The goal of the project is to analyze how different algorithms perform on music genre classification and understand their strengths and limitations.

This project was implemented in Jupyter Notebook using Python libraries such as pandas, scikit-learn, matplotlib, and numpy.
