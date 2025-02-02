# UASNET
This repository contains the implementation of an integrated framework for Multiple Sclerosis (MS) lesion segmentation and classification of abnormalities in the Sensory, Motor, and Visual systems. The framework fuses MRI-derived texture features with clinical metadata to enhance the precision of MS lesion detection and classification.

### Key Features
U-Net Attention SqueezeNet (UASNet): A specialized U-Net model incorporating Attention and Squeeze-and-Excitation (SE) blocks for high-precision segmentation of MS lesions on T2-weighted MRI images, achieving 98.82% segmentation accuracy.
Feature Extraction: Extraction of 21 texture features from segmented MRI images combined with clinical data for comprehensive analysis.
Integration of Imaging and Clinical Data: This approach aims to facilitate more accurate and personalized diagnosis and treatment strategies for MS.
Feature Correlation: Pearson, Spearman's Rank, and Kendall's Tau correlation methods were used to analyze relationships between features.
Feature Selection: Application of Chi-Square feature selection to improve classification performance.
Machine Learning Classifiers: Traditional classifiers like Decision Trees, Random Forests, Naive Bayes, and Logistic Regression were employed for evaluation.
Graph-Based Learning: GCN, GAT, GraphSAGE, VGAE, DGI & GIN  were tested classifying motor, visual & sensory system abnormalities. 
