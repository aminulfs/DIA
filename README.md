🎯 Project Overview
Drug-Induced Autoimmunity (DIA) is a serious adverse drug reaction where medications trigger the immune system to attack the body's own tissues. This project develops an interpretable machine learning system to identify DIA risk during preclinical drug development, potentially preventing costly clinical trial failures and patient harm.

Key Features
87.5% Accuracy with optimized 0.4 threshold
90% Recall - catches 27 out of 30 DIA-positive drugs
ROC-AUC: 0.939 - excellent discrimination
Interpretable predictions using SHAP values
Production-ready deployment pipeline
📊 Dataset
Source
UCI Machine Learning Repository - Drug-Induced Autoimmunity Dataset

Statistics
Split	Total	Negative (Safe)	Positive (DIA)	Ratio
Training	477	359 (75%)	118 (25%)	3:1
Test	120	90 (75%)	30 (25%)	3:1
Features
196 molecular descriptors generated using RDKit
Categories: Physicochemical properties, topological indices, functional groups, surface area descriptors
No missing values - clean dataset
