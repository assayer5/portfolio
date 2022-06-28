## [Project 1: E. coli Promoter Sequence Classification](https://github.com/assayer5/ecolipromoter)

#### Overview
Classified E. coli sequences as promoter or non-promoter using k-mer counting and a naive bayes classifier on the UCI Machine Learning Repository: Molecular Biology (Promoter Gene Sequences) Data Set.
Final model scored a mean accuracy of 0.9125 with 5-fold cross validation and an accuracy of 0.9259 on the test set.

tags: classification, feature engineering, k-mer counting, confusion matrix, pandas, sklearn


## [Project 2: Microarray Leukemia Classification](https://github.com/assayer5/microarray-leukemia-classif)

#### Overview
Classified microarray samples as Acute Lymphoblastic Leukemia (ALL) or Acute Myeloid Leukemia (AML) using a support vector classifier (SVC) on a small subset of the normalized intensity values of 7,129 genes from microarray samples generated by Golub, et al.
Final model scored a mean accuracy of 0.946 with 5-fold cross validation on the training set and classified samples with an accuracy of 0.882 on the test set.

tags: classification, feature selection, correlation matrix, scipy, seaborn, pandas


## [Project 3: Image Classification with Neural Networks](https://github.com/assayer5/cnn-flower-classif)

#### Overview
Classified ~100 different flower types with a convolutional neural network. Images were drawn from 5 public data sets to generate a [Kaggle image classification competition](https://www.kaggle.com/c/tpu-getting-started/overview). Model scored an accuracy of 0.8025 on the validation set and an accuracy of 0.7624 on the Kaggle test set.

tags: classification, neural network, cnn, tensorflow, keras


## [Project 4: Analysis of Yelp Restaurant Reviews](https://github.com/assayer5/yelp-restaurant-reviews)

#### Overview
Analysis of 2M+ Yelp users and 5M+ restaurant reviews to develop a data driven strategy to pick a delicious meal, applying VADER sentiment analysis and visualized with matplotlib, seaborn. Data processing adapted to work for distributed computing with PySpark.

tags: pandas, matplotlib, seaborn, numpy, nltk, sentiment analysis, pyspark, distributed computing

## [Project 5: Data Accession via API](https://github.com/assayer5/VCF-annotation)

#### Overview
Parsed a VCF file to generate queries to an API, annotating the variants with API response. 

tags: pandas, API, requests, json
