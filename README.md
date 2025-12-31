# Pneumonia Detection using CNN

## Overview
This project focuses on detecting **pneumonia from chest X-ray images** using deep learning.
Several CNN-based architectures were implemented and compared to identify the most effective model.

## Dataset
- **Source**: Kaggle – Pediatric Chest X-ray Dataset
- **Images**: 5,863 chest X-ray images
- **Classes**: Normal, Pneumonia
- **Patients**: Children aged 1–5 years

> Dataset is not included in this repository due to size constraints.

## Models Implemented
- Custom CNN
- AlexNet
- ResNet50 (Transfer Learning)
- CNN with CBAM (Channel & Spatial Attention)

## Methodology
1. Data preprocessing & class distribution analysis  
2. Image augmentation using `ImageDataGenerator`  
3. Model training and validation  
4. Performance evaluation using:
   - Accuracy
   - Confusion Matrix
   - Precision, Recall, F1-score  

## Results (Test Accuracy)
| Model | Accuracy |
|------|---------|
| Custom CNN | XX% |
| AlexNet | XX% |
| ResNet50 | XX% |
| CNN + CBAM | **XX%** |

> CBAM-enhanced CNN achieved the best overall performance.

## Tools & Technologies
- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib, Seaborn
- Kaggle

## How to Run
```bash
