# Crop Type Mapping from Satellite Images Using CNN

## Project Overview

This project focuses on Crop Type Mapping and Land Cover Classification using satellite imagery and Deep Learning techniques. A Convolutional Neural Network (CNN) was developed to classify satellite images into different land-cover categories using the EuroSAT dataset.

The project was completed as part of the Machine Learning course and demonstrates the application of image classification techniques in agricultural and environmental monitoring.

---

## Dataset

**Dataset Name:** EuroSAT Dataset

**Source:** https://www.kaggle.com/datasets/apollo2506/eurosat-dataset

### Dataset Information

- Total Images: 27,000
- Number of Classes: 10
- Image Type: RGB Satellite Images
- Source Satellite: Sentinel-2

### Classes

1. AnnualCrop
2. Forest
3. HerbaceousVegetation
4. Highway
5. Industrial
6. Pasture
7. PermanentCrop
8. Residential
9. River
10. SeaLake

---

## Project Objectives

- Develop a CNN model for satellite image classification.
- Perform image preprocessing and augmentation.
- Evaluate model performance using standard metrics.
- Compare CNN performance with a Transfer Learning model.
- Generate visualizations and classification reports.

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Project Workflow

1. Dataset Loading
2. Data Preprocessing
3. Image Resizing and Normalization
4. Data Augmentation
5. Train/Validation/Test Split
6. CNN Model Development
7. Model Training
8. Model Evaluation
9. Transfer Learning Comparison
10. Result Visualization

---

## Model Architecture

### CNN Model

- Conv2D Layer (32 Filters)
- MaxPooling Layer
- Conv2D Layer (64 Filters)
- MaxPooling Layer
- Conv2D Layer (128 Filters)
- MaxPooling Layer
- Flatten Layer
- Dense Layer (128 Units)
- Dropout Layer
- Output Layer (10 Classes)

---

## Evaluation Metrics

The following metrics were used:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report
- ROC Curve

---

## Generated Outputs

The project generates:

- Accuracy Curve
- Loss Curve
- Confusion Matrix
- Classification Report
- ROC Curve
- Heatmap Visualizations
- Sample Predictions

---

## Folder Structure

```
Crop-Type-Mapping-CNN/
│
├── dataset/
├── notebooks/
├── models/
│   ├── cnn_model.h5
│   └── mobilenet_model.h5
├── outputs/
│   ├── accuracy_curve.png
│   ├── loss_curve.png
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   └── heatmap.png
├── README.md
└── requirements.txt
```

---

## How to Run

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/crop-type-mapping-cnn.git
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run Notebook

Open:

```bash
Crop_Type_Mapping_CNN.ipynb
```

and execute all cells.

---

## Research Questions

1. Can CNN models accurately classify satellite images into different crop and land-cover categories?

2. Which land-cover classes achieve the highest classification accuracy?

3. Does transfer learning improve classification performance compared to a custom CNN model?

4. What image features contribute most to classification accuracy?

---

## Future Improvements

- Implement Grad-CAM visualization
- Hyperparameter tuning
- Advanced Transfer Learning Models
- Satellite Time-Series Analysis
- Real-Time Crop Monitoring

---

