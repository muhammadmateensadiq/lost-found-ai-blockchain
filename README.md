# Lost & Found AI + Blockchain  
### Deep Learning Image Classification Framework for Lost-and-Found Item Management

This repository contains the complete implementation of the **AI-based image classification module** used in the research paper:

**“Blockchain and AI-Based Platform for Managing Lost and Found Items in Public Places.”**

---

## Features

The notebook demonstrates:
- Custom filtering of Caltech-256 to 10 highly relevant lost-and-found item categories  
- Strong data augmentation and ablation study (with vs without augmentation)  
- Training & evaluation of ResNet50, VGG16, and MobileNetV3  
- 5-fold stratified cross-validation  
- Comprehensive metrics: accuracy, precision, recall, F1-score, macro-AUC, per-class analysis  
- High-resolution plots (300 DPI): learning curves, ROC curves, confusion matrices, per-class metrics  
- Robustness testing against Gaussian blur (real-world scenario)

**Dataset link:**  
[Caltech-256 Dataset](https://www.kaggle.com/datasets/jessicali9530/caltech256)

## Installation

### 1. Clone the Repository
        git clone https://github.com/muhammadmateensadiq/lost-found-ai-blockchain.git
        cd lost-found-ai-blockchain

### 2. Install Dependencies
        pip install -r requirements.txt

### 3. Prepare Dataset
   - Download Caltech-256 and place it in your environment.
   - Update the dataset path in the notebook.
     - For Kaggle: dataset_folder = '/kaggle/input/caltech256/256_ObjectCategories'
     - For local/Colab: adjust accordingly

### 4. Run the Notebook
   - Open lost-found-ai-blockchain.ipynb
   - Run all cells to reproduce experiments.
