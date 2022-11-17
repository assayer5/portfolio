## [Project: Multimodal single cell NGS data](https://github.com/assayer5/multimodal-single-cell)

#### Overview
Multimodal single cell NGS data (Multiome and CITE-seq) utilized for multioutput regression. For the CITE-seq dataset, scRNA-seq data is used to predict surface protein expression with ensemble model of boosted trees and regularized regression. For the Multiome dataset, ATAC-seq data is used to predict gene expression with a neural network.

tags: sparse data, anndata, ensemble learning, regression, xgboost, pytorch, neural network

## [Project: Analysis of Yelp Restaurant Reviews](https://github.com/assayer5/yelp-restaurant-reviews)

#### Overview
Analysis of 2M+ Yelp users and 5M+ restaurant reviews to develop a data driven strategy to pick a delicious meal, applying VADER sentiment analysis and visualized with matplotlib, seaborn. Data processing adapted to work for distributed computing with PySpark.

tags: pandas, nltk, sentiment analysis, pyspark, distributed computing


## [Project: Data Accession via API](https://github.com/assayer5/VCF-annotation)

#### Overview
Parsed a VCF file to generate queries to an API, annotating the variants with API response. Unit tested functions.

tags: pandas, API, requests, json, unit testing


## [Project: E. coli Promoter Sequence Classification](https://github.com/assayer5/ecolipromoter)

#### Overview
Classified E. coli sequences as promoter or non-promoter using k-mer counting on the UCI Machine Learning Repository: Molecular Biology (Promoter Gene Sequences) Data Set.
Naive bayes classifier and logistic regression yielded similar results in 5-fold cross validation and test set accuracy.

tags: classification, feature engineering, k-mer counting, confusion matrix, pandas, sklearn


## [Project: Microarray Leukemia Classification](https://github.com/assayer5/microarray-leukemia-classif)

#### Overview
Classified microarray samples as Acute Lymphoblastic Leukemia (ALL) or Acute Myeloid Leukemia (AML) using a support vector classifier (SVC) on a small subset of the normalized intensity values of 7,129 genes from microarray samples generated by Golub, et al.
Final model scored a mean accuracy of 0.946 with 5-fold cross validation on the training set and classified samples with an accuracy of 0.882 on the test set.

tags: classification, feature selection, correlation matrix, scipy, seaborn, pandas


## [Project: Image Classification](https://github.com/assayer5/cnn-flower-classif)

#### Overview
Classified ~100 different flower types with a convolutional neural network. Images were drawn from 5 public data sets to generate a [Kaggle image classification competition](https://www.kaggle.com/c/tpu-getting-started/overview). Model scored an accuracy of 0.8424 on the validation set and an accuracy of 0.79649 on the Kaggle test set.

tags: classification, neural network, cnn, tensorflow, keras
