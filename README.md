
# 😷 Mask Detection Using Deep Learning

This project uses deep learning to detect whether a person is wearing a mask or not in an image using VGG16. It leverages Convolutional Neural Networks (CNNs) for binary classification between **with_mask** and **without_mask** images.

## 📁 Dataset
The dataset used contains two categories:
- `with_mask`
- `without_mask`

Images were resized to `224x224` and loaded using OpenCV. You can place the dataset in the following structure:

```
dataset/
└── train/
    ├── with_mask/
    └── without_mask/
```

## 🧠 Model Architecture
- CNN-based architecture using Keras and TensorFlow
- Trained for **5 epochs**
- Final validation accuracy: **96.88%**
- Loss reduced from **0.80** to **0.17**


## 📊 Results
The model performed well with high accuracy and generalization across test data.

| Epoch | Validation Accuracy | Loss    |
|-------|---------------------|---------|
| 1     | 88.12%              | 0.80    |
| 5     | **96.88%**          | **0.17**|


