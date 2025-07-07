# 🧠 E-Waste Generation Classification using EfficientNetV2B0

This project uses **EfficientNetV2B0** with data augmentation to classify e-waste images into 10 categories, aiding sustainable waste management.

## 📁 Dataset

* Provided by mentor (originally sourced from Kaggle)
* Contains images of: Battery, Mobile, PCB, Printer, etc.
* `dataset.zip` is included for easy access.

## 📊 Features

* Transfer learning with EfficientNetV2B0
* Validation split, dropout, early stopping
* Achieved **97% accuracy** on test data
* Real-time prediction interface with **Gradio**

## 🧪 Output Samples

### 📊 Training Accuracy & Loss
![Accuracy Graph](Media/training_graphs.png)

### 📉 Confusion Matrix
![Confusion Matrix](Media/Confusion_matrix_graphic.png)

### 🧪 Sample Predictions
![Sample Predictions](Media/Sample_predictions_immagespng.png)

### 🌐 Gradio Interface
![Interface Screenshot](Media/E Waste Image Classifier Interface with Audio Player Image.png)


## 🔮 Future Scope

* Multi-label classification (e.g., hybrid devices)
* On-device lightweight model
* Recycle center integration

## 🚀 Running the Model

```python
from tensorflow.keras.models import load_model
model = load_model('Efficient_classify_final.keras')
```
