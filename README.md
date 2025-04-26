# Transfer Learning with Pre-trained DenseNet121

This repository contains a Google Colab implementation of **transfer learning** using a **pre-trained DenseNet121** model on the **UEH-VDR (Vietnamese Dish Recognition)** dataset.  
It demonstrates how to efficiently adapt a high-performance model for new image classification tasks.

---

## ✨ Features

- **Pre-trained DenseNet121**: Loaded from torchvision models.
- **Fine-tuning**: Updated the classifier layer to suit the number of target classes.
- **Data Augmentation**: Performed random resizing, cropping, and normalization for better generalization.
- **Efficient Training**: Leveraged GPU acceleration in Google Colab.
- **Prediction Visualization**: Displayed sample test images with model predictions.

---

## 📂 Dataset

Dataset used:

**UEH-VDR (Vietnamese Dish Recognition Dataset)**  
[Kaggle Link](https://www.kaggle.com/datasets/truthtaicom/uehvdr-dataset)

Please download the dataset from Kaggle, upload it to your Google Drive, and access it in Colab.

---

## 🛠 Requirements

This notebook is optimized to run on **Google Colab**.  
If you wish to run it locally, you will need:

```bash
pip install torch torchvision matplotlib numpy
