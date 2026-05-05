#  Deep Learning-Based Drug Response Prediction (Breast Cancer)

##  Overview
This project develops a computational pipeline for predicting **drug response in breast cancer patients** by integrating:
* TCGA multi-omics data
* GDSC drug sensitivity data
* Deep learning models
The goal is to simulate a **precision medicine framework** that ranks drugs based on predicted sensitivity.
---
##  Methodology
### 1. Data Integration
* TCGA (patient gene expression)
* GDSC (drug response and pathways)
* Aligned using cancer type (BRCA)
---
### 2. Representation Learning
* Autoencoder used to extract **latent patient embeddings**
* Captures underlying biological variation
---
### 3. Drug Response Modeling
* Deep neural network trained on:
  * patient embeddings
  * drug identity
  * pathway features
* Output: **Predicted LN(IC50)**
---
### 4. Biological Grounding
* Incorporated:
  * drug target pathways
  * cancer-specific filtering
* Ensures mechanistic relevance
---
## 🚀 Live Project Demo
 https://somshirsha.github.io/Precision-drug-response-prediction/
---
##  Results
* Generated **patient-specific drug rankings**
* Identified key pathways:
  * Mitosis
  * Cell cycle regulation
  * Protein degradation
* Observed:
  * strong global drug signals
  * moderate patient-specific variation
---
##  Visualizations
* PCA clustering of patients
* Drug sensitivity heatmaps
* Drug variability analysis
* Drug–pathway interaction network
---
##  Limitations
* No direct TCGA–GDSC pairing
* Limited personalization due to dataset constraints
* Requires CCLE integration for full alignment
---
##  Future Work
* Integrate CCLE gene expression data
* Apply multimodal deep learning
* Enhance patient-specific prediction accuracy
---
##  Tech Stack
* Python
* PyTorch
* Scikit-learn
* Pandas, NumPy
* Seaborn, Matplotlib
* NetworkX
---
##  Key Takeaway

This project demonstrates a **deep learning-driven, biologically informed framework** for drug response prediction, bridging bioinformatics and AI in precision medicine.

