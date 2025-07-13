# Plant-Disease_Pre-trained_CNN

🍃 Plant Disease Classification Using Pre-trained CNNs
This project focuses on classifying plant leaf diseases by leveraging Convolutional Neural Networks (CNNs). It utilizes multiple pre-trained CNN models with PyTorch for transfer learning, enabling high accuracy and efficient training.

📂 Dataset
The dataset used in this project is publicly available on Kaggle:

Dataset: Plant Disease Dataset

Local Path Used: /kaggle/input/plant-disease/Plant_Disease_Dataset


Classes:

Healthy

Powdery (Powdery Mildew)

Rust


Total Images per Class:
Approximately 510 images per class, resulting in around 1,530 images in total.

Dataset Split:

Training: 70%

Validation: 15%

Testing: 15%

🧠 Model Architectures
This project employs transfer learning with several pre-trained CNN architectures. The final fully connected layers in each model were modified to output predictions for 3 classes.

✅ Models Implemented:

ResNet50

VGG16

MobileNet v2

GoogLeNet

All models were fine-tuned and evaluated on the same dataset to ensure a fair comparison in terms of accuracy, loss, and inference speed.
