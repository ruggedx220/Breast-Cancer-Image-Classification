# Breast-Cancer-Image-Classification
# Introduction
Ultrasound imaging is a valuable diagnostic tool in the field of medical imaging, especially for cancer diagnosis. Accurate classification of cancerous and non-cancerous lesions in ultrasound images is critical for early detection and effective treatment planning. In recent years, Convolutional Neural Networks (CNNs) and Transfer Learning have emerged as powerful techniques for improving the accuracy and efficiency of medical image classification tasks.


![purple Cancer](https://github.com/ruggedx220/Breast-Cancer-Image-Classification/blob/main/Cancer%20Images/purple-can.jpg
)

# Dataset
In 2018, a comprehensive dataset was collected and pre-processed from Baheya Hospital for Early Detection and Treatment of Women’s Cancer, Cairo (Egypt). Focusing on the breast ultrasound images from a diverse group of women aged between 25 and 75 years, this dataset comprises of a substantial sample size of 600 female patients, contributing to the richness and representativeness of the collected data. The dataset encompasses a total of 780 high-resolution images, with an average size of 500*500 pixels, meticulously curated to capture various aspects of breast health and pathology.
![ultra sound](https://github.com/ruggedx220/Breast-Cancer-Image-Classification/blob/main/Cancer%20Images/malignant%20(95).png) ![ultra sound](https://github.com/ruggedx220/Breast-Cancer-Image-Classification/blob/main/Cancer%20Images/malignant%20(95).png)

# Convolutional Neural Networks (CNNs)
CNNs are a class of deep learning models designed specifically for image recognition tasks. They excel at automatically learning relevant features from images, making them well-suited for tasks like ultrasound image classification. The key components of a CNN are convolutional layers, pooling layers, and fully connected layers. These layers work together to learn hierarchical representations of features in the images, which are crucial for distinguishing between cancerous and healthy tissue.
# Transfer Learning
Transfer learning is a machine learning technique that leverages pre-trained neural network models on large datasets for a specific task and adapts them to a new, related task with a smaller dataset. In the context of cancer ultrasound image classification, transfer learning can significantly boost model performance. Researchers can use pre-trained CNN architectures, such as VGG16, ResNet, or Inception, which have already learned valuable image features from massive datasets like ImageNet. By fine-tuning these models on ultrasound images, you can leverage their knowledge to improve accuracy while requiring fewer labeled medical images.
# Objectives
The focus of this project is to train and compare the results of simple convolutional nueral networks against pre-trained transfer learning algorithms. 
