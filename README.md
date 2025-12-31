# Pneumonia Detection using CNN

## Overview
This project focuses on detecting **pneumonia from chest X-ray images** using deep learning.
Several CNN-based architectures were implemented and compared to identify the most effective model.

## Dataset
- **Name**: Pediatric Chest X-ray (Pneumonia)
- **Source**: Kaggle
- **Link**: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
- **Total Images**: 5,863
- **Classes**: Normal, Pneumonia

> The dataset is not included in this repository due to size limitations.
> Please download it directly from Kaggle and place it in the appropriate directory if you wish to run the notebook locally.

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
