# Bone Anomaly Detection on MURA Dataset

## Project Description

This project focuses on automated bone anomaly detection from X-ray images using deep learning. The approach involves a two-stage process developed and demonstrated in Jupyter notebooks:

1. **Body Part Classification**: First, a model predicts which body part (wrist, elbow, etc.) the X-ray belongs to.
2. **Anomaly Detection**: Based on the predicted body part, a dedicated model assesses whether the image is normal or abnormal.
3. **Explainability**: Grad-CAM visualizations are provided for interpretable predictions, highlighting regions influencing the model's decisions.

Both stages use the ResNet-18 architecture. The implementation is modular, allowing extension to other architectures or datasets.

## Dataset

**MURA (Musculoskeletal Radiographs)** is one of the largest public radiographic image datasets, released by the Stanford ML Group. It consists of over 40,000 images from studies on seven upper extremity body parts — elbow, finger, forearm, hand, humerus, shoulder, and wrist. Each study is labeled as either normal or abnormal.  
*Note: The dataset is not provided in this repository. Please obtain it from the [Stanford ML Group MURA website](https://stanfordmlgroup.github.io/competitions/mura/).*


## Requirements

- Python 3.8 or above
- PyTorch
- torchvision
- numpy
- matplotlib
- opencv-python
- pandas
- tqdm


