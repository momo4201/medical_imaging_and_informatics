# Medical Imaging and Informatics 🩻
## Overview
This repository contains the implementations and hands-on project completed during the **GIAN (Global Initiative of Academic Networks)** course on Artificial Intelligence and Medical Image Informatics for Cross-Scale Disease Characterization and Precision Medicine.
These projects have strengthened my conceptual understanding of the use of AI in the context of clinical imaging.
## 🗂️ Repository Contents
### Phase 1: Medical Image Preprocessing & Radiomics
* **`basics_of_medical_imaging.ipynb`**
 Learned how to load, visualize, and preprocess medical images, perform normalization and edge detection, work with pathology whole-slide images, and explore common public imaging datasets.
- **`basics_of_Radiomics.ipynb`** – Introduction to PyRadiomics and the radiomics workflow, including ROI-based feature extraction from CT/MRI/PET images and their use in machine learning applications.

### Phase 2: Foundation Models in Radiology
* **`foundation_model_radiology.ipynb`
* **Objective:** Understand how modern foundation models can be applied to radiology and other medical imaging tasks.
* Explored different pre-trained medical AI models including Chest X-ray foundation models, BioViL, MedCLIP, MedSAM, and MONAI-based architectures. Compared their capabilities for image understanding, vision-language learning, classification, and segmentation in healthcare applications.

* * **`MedSam_segmentation.ipynb`
  * **Objective:** Learn how foundation models can be used for automated medical image segmentation.
  * Implemented the Medical Segment Anything Model (MedSAM) for segmenting regions of interest from medical images. Generated image embeddings, applied bounding-box prompts, and visualized segmentation masks to understand prompt-based segmentation workflows.
 
### Phase 3: Automated Machine Learning Pipelines
* **`optuna_classification_pipeline.ipynb`
* **Objective:** Develop an automated machine learning workflow for classifying lung cancer histology subtypes using radiomic features extracted from CT scans.
* Performed data preprocessing, feature selection, label encoding, and train-test splitting.
* Used Optuna to automatically optimize feature count, model selection, and hyperparameters across Support Vector Machine (SVM), Logistic Regression, Decision Tree, and Random Forest classifiers.
* Evaluated models using stratified cross-validation and ROC-AUC, with the best-performing configuration identified as an optimized Decision Tree classifier.

## 🛠️ Technologies & Frameworks  
* **Languages:**  Python
* **Medical Imaging & Radiomics:**  PyRadiomics, SimpleITK, OpenCV
* **Deep Learning & Foundation Models:**  PyTorch, Hugging Face Transformers, TorchXRayVision, MONAI
* **Machine Learning:**  Scikit-learn, Optuna

## 🚀 Execution & Reproducibility
All workflows in this portfolio were developed using **Google Colab**, ensuring zero-overhead environment configuration and complete reproducibility.
