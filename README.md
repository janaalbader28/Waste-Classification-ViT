## Waste Classification Model using Vision Transformer (ViT) 🗑️♻️

This project aims to classify waste materials using a Vision Transformer (ViT) model. The dataset used for this project is the **Garbage Classification Dataset**, which contains images of different types of garbage. The goal is to develop a deep learning model capable of accurately categorizing these images into distinct categories of waste.

The model architecture is based on **Vision Transformer (ViT)**, which is a state-of-the-art transformer model designed for image classification tasks.

### Dataset 📂

You can download the dataset from the following link:

[Garbage Classification Dataset on Kaggle](https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification/data)

### Performance Metrics 📈 📊

The following table summarizes the performance of the ViT model on the waste classification task compared to CNN models such as DenseNet, EfficientNet, and ResNet. The metrics include Accuracy, Precision, Recall, and F1-Score.


| Model                     | Accuracy (%) | Precision (%) | Recall (%) | F1-Score (%) |
|---------------------------|--------------|---------------|------------|--------------|
| Vision Transformer (ViT)   |          89%    |         90%      |      89%      |       89%       |
| DenseNet121                 |            95%  |        95%       |         95%   |95%|
| EfficientNet_b0             |          96%    |     96%          |         96%   |          96%    |
| ResNet50                    |            94%  |          94%     |95%      |94%       |

💡 **Note:** These results are based on the model evaluations for 5 epochs. You can adjust the number of epochs based on your training settings.

