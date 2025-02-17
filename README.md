# Overview
This repository containts a Face Mask Detection Model fine-tuned from the Faster R-CNN (PyTorch). The model is trained to detect faces and whether they are wearing mask or not.

# Model
Faster R-CNN (PyTorch) model, fine-tuned to detect faces with or without mask.

# Data
Training data from Kaggle: https://www.kaggle.com/datasets/wobotintelligence/face-mask-detection-dataset
The original dataset contains 4269 images and 20 different labels, including a category for "face covering." For this project, I filtered the dataset to only include the labels 'face_with_mask' and 'face_no_mask'. 3469 images are used for training, 400 for validatoin, 400 for test.

# Example result
![image](https://github.com/user-attachments/assets/c7ee1be0-618a-43f4-bb42-a52528ece4b2)


# Evaluation
| Metric                     | Value     |
|----------------------------|-----------|
| **Training Loss**          | 0.0594    |
| **Validation mAP@0.5**     | 97.66%    |
| **Validation mAP@0.75**    | 94.38%    |
| **Validation IoU**         | 90.53%    |
| **Testing mAP@0.5**        | 97.41%    |
| **Testing mAP@0.75**       | 93.85%    |
| **Testing IoU**            | 90.18%    |

# References
- Dataset: https://www.kaggle.com/datasets/wobotintelligence/face-mask-detection-dataset
