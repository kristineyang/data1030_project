This project, "Predicting Gene Transcriptional Activity Using 3D Spatial Genomic Data", was completed for DATA1030 (Fall 2024). The goal of this project is to classify the transcriptional activity of genes  ('on' or 'off') using spatial genomic data. Four supervised machine learning models were implemented and tested. 






The original dataset came from "Genome-Scale Imaging of the 3D Organization and Transcriptional Activity of Chromatin" by Jun-Han Su et al. (2020). 
It was too large to store on github, but it can be accessed here: https://zenodo.org/records/3928890

In the 'results' folder, the model results for Logistic Regression and KNN exceeded the size limit for github, so all three pkl files for each model were compressed into a .zip file. 

```yaml
channels:
  - conda-forge

dependencies:
  - python=3.12.5
  - matplotlib=3.9.2
  - plotly=5.23.0
  - pandas=2.2.2
  - scikit-learn=1.5.1
  - numpy=1.26.4
  - py-xgboost=2.1.1
  - shap=0.45.1
  - jupyter

prefix: /opt/conda
