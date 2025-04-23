## Waste Classification Model using Vision Transformer (ViT) 🗑️♻️

This project explores the application of **Vision Transformers (ViT)** in the field of **waste classification**, an area where ViT has not been extensively studied. While Convolutional Neural Networks (CNNs) such as **DenseNet**, **EfficientNet**, and **ResNet** have been widely used for image classification tasks, our research aims to evaluate the potential of ViT in this domain and compare its performance against these established CNN architectures.

We demonstrate that ViT can achieve strong performance in classifying waste materials, highlighting its ability to extract meaningful features from visual data even in a domain traditionally dominated by CNNs.

### 🗃️ Dataset

We used the **Garbage Classification Dataset**, which contains images of different types of waste.  
📎 [Garbage Classification Dataset on Kaggle](https://www.kaggle.com/datasets/asdasdasas/garbage-classification/data)

### 📊 Performance Metrics

The table below summarizes the performance of ViT compared to popular CNN models. The metrics include **Accuracy**, **Precision**, **Recall**, and **F1-Score**, calculated over 50 training epochs.

| Model                      | Accuracy (%) | Precision (%) | Recall (%) | F1-Score (%) |
|----------------------------|--------------|---------------|------------|--------------|
| Vision Transformer (ViT)   | 95%          | 95%           | 95%        | 95%          |
| DenseNet121                |  95%          | 95%           | 95%        | 95%          |
| EfficientNet_b0            | 97%           | 97%           | 97%          | 97%           |
| ResNet50                   | 93%           | 93%            | 93%         | 93%           |
