# Lost & Found AI + Blockchain  
### Deep Learning Image Classification Framework for Lost-and-Found Item Management

This repository contains the complete implementation of the **AI-based image classification module** used in the research paper:

**“Blockchain and AI-Based Platform for Managing Lost and Found Items in Public Places.”**

---

## Features

The notebook demonstrates:
- Data preprocessing and augmentation
- Custom dataset handling
- Training deep learning models (ResNet50, VGG16, MobileNetV3) with PyTorch
- Evaluation with metrics, confusion matrix, ROC curves, and robustness testing on noisy images
- 5-fold cross-validation for model selection

**Dataset link:**  
[Caltech-256 Dataset](https://www.kaggle.com/datasets/jessicali9530/caltech256)

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/muhammadmateensadiq/lost-found-ai-blockchain.git
cd lost-found-ai-blockchain

2. Install Dependencies
pip install -r requirements.txt

3. Prepare Dataset
Download Caltech-256 and place it in your environment (Kaggle, local machine, etc.).

Update the dataset path in the notebook:

dataset_folder = '/kaggle/input/caltech256/256_ObjectCategories'

4. Run the Notebook
Open:
lost-found-ai-blockchain.ipynb
Run all cells to reproduce experiments.
