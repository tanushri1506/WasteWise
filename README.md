# WasteWise – AI-Powered Waste Classification System

## Project Overview
WasteWise is a deep learning–based computer vision project that classifies waste images into **Organic** and **Recyclable** categories using a custom **Convolutional Neural Network (CNN)**. The project demonstrates an end-to-end ML pipeline from data preprocessing to model evaluation.

## Dataset
- **Source:** Waste Classification Dataset (Kaggle)
- **Total Images:** 25,000+
- **Data Split:**
  - Training: ~18,000 images
  - Validation: ~4,500 images
  - Test: ~2,500 images
- **Classes:**
  - Organic (O)
  - Recyclable (R)

## Tech Stack
- **Language:** Python  
- **Framework:** TensorFlow, Keras  
- **Libraries:** NumPy, Pandas, OpenCV, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook (Kaggle)

## Methodology
1. Performed exploratory data analysis and class distribution analysis  
2. Applied image preprocessing and augmentation (rotation, zoom, flip, shift)  
3. Designed and trained a custom CNN architecture  
4. Used Adam optimizer with categorical cross-entropy loss  
5. Evaluated model using accuracy, confusion matrix, and classification report  

---

## Model Architecture
- Input: 150 × 150 × 3  
- Convolution + MaxPooling layers  
- Batch Normalization and Dropout  
- Fully connected Dense layers  
- Softmax output layer (2 classes)

## Results
- **Test Accuracy:** 85.3%

### Classification Report
| Class        | Precision | Recall | F1-Score |
|--------------|-----------|--------|----------|
| Organic      | 0.89      | 0.84   | 0.86     |
| Recyclable  | 0.81      | 0.87   | 0.84     |

## Key Learnings
- Data augmentation significantly improves generalization
- CNNs perform well for binary image classification
- Proper regularization helps reduce overfitting

## Future Work
- Apply transfer learning (ResNet, MobileNet, EfficientNet)
- Hyperparameter tuning
- Deploy as a web application
- Extend to multi-class waste classification

## Contact
**Tanushri Barsainya**  
GitHub: https://github.com/tanushri1506  
LinkedIn: https://www.linkedin.com/in/tanushri1506/
