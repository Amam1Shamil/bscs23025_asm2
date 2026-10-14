# Fine-Tuning ResNet-50 and U-Net on Small Image Datasets
**ANN & Deep Learning — Assignment 02**

**Author:** Fraz Liaqat  
**Roll Number:** BSCS23133  
**Institution:** Information Technology University (ITU), Lahore  

---

## 📌 Project Overview
Training deep learning models from scratch requires tens of thousands of labeled images. This project demonstrates the power of **Transfer Learning** and **Fine-Tuning** on small image datasets (~150 to 200 samples) across two core computer vision tasks:
1. **Multi-Class Image Classification:** Fine-tuning an ImageNet-pretrained **ResNet-50** on a 5-class subset of the Oxford Flowers-102 dataset (200 images total).
2. **Binary Semantic Segmentation:** Fine-tuning a **U-Net** with an ImageNet-pretrained ResNet-50 encoder on a subset of the Oxford-IIIT Pet dataset (150 image-mask pairs).

---

## 📂 Repository Structure
```text
BSCS23133-assignment2/
│
├── notebook/
│   └── bscs23133_asm02.ipynb         # Executed Google Colab notebook with outputs
│
├── results/
│   ├── resnet_results.png            # ResNet-50 loss & accuracy curves
│   ├── resnet_confusion_matrix.png   # ResNet-50 test set confusion matrix
│   ├── unet_curves.png               # U-Net loss, Dice, and IoU curves
│   └── unet_predictions.png          # Input | Ground Truth | Prediction | Overlay
│
└── README.md                         # Documentation
