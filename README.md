# Deep Learning Based Multi-Class Tissue Characterisation In Colorectal Histopathology Images

MSc Research Project — Ulster University, Manchester, UK

## Author
**Ghulam Mustafa**  
MSc Computer Science and Technology  
📧 Mustafa-G5@ulster.ac.uk

## Project Summary
This project implements and compares six pre-trained CNN architectures for the multi-class classification of colorectal cancer histopathology images into 8 tissue types.

## Dataset
- **Colorectal_Histology_MNIST** (Kather et al., 2016)
- 5,000 H&E-stained images, 150×150 pixels
- 8 balanced classes (625 images each):
  Tumour, Stroma, Complex, Lymphocyte, Debris, Mucosa, Adipose, Empty
- **Dataset Link:** https://www.kaggle.com/datasets/user322312312/kather-texture-2016-image-tiles-5000-1

## Models Compared
- VGG-16
- VGG-19
- ResNet-50
- ResNet-152V2
- Inception-V3
- **EfficientNet-B4**  (Best — 95.46%)

## Results

| Model | Accuracy |
|-------|----------|
| VGG-16 | 51.71% |
| VGG-19 | 59.86% |
| ResNet-50 | 78.94% |
| ResNet-152V2 | 76.84% |
| Inception-V3 | 89.86% |
| **EfficientNet-B4** | **95.46%** |

## Tools Used
Python, TensorFlow, Keras, Google Colab, Jupyter Notebook
