# Brain Tumor Detection using CNN and Vision Transformers (ViT)
Overview
This project aims to detect brain tumors from MRI scans using deep learning methodologies. Specifically, the models employed are Convolutional Neural Networks (CNN) and Vision Transformers (ViT), both of which are compared on their performance metrics.

Problem Statement
A brain tumor represents a growth of abnormal cells in your brain. They can be either noncancerous (benign) or cancerous (malignant) and may originate in the brain (primary tumors) or spread from other body parts (secondary tumors). The growth rate and location of a brain tumor affect the nervous system functionality. Treatment varies based on the tumor type, size, and location. Our goal is to develop a deep learning system that can assist in diagnosing these tumors efficiently.


Models Overview
Convolutional Neural Network (CNN)
CNNs are commonly applied to analyze visual imagery and are known for their ability to detect features from images, making them suitable for tasks like image classification, segmentation, and more. CNNs work well even with smaller data volumes due to their architectural efficiencies which include shared weights and translation invariance.


Vision Transformer (ViT)
ViTs, on the other hand, treat the image as a sequence of patches and apply transformer mechanisms to process these patches. This model can potentially capture more global and comprehensive relationships in the data but requires larger and more varied datasets for optimal training.


Data
The data consists of MRI images categorized into 'yes' (with tumor) and 'no' (without tumor). These images are used to train and evaluate the performance of the CNN and ViT models.

Experimentation and Results
The models were trained using a standard deep learning workflow involving data preprocessing, model training, and evaluation. Performance metrics such as accuracy, precision, and recall were compared.

Usage
Details on how to run and use the models for predictions are provided in the respective Jupyter notebooks.

Conclusion
Both CNN and ViT models have shown promise in the task of brain tumor detection. Choosing the right model depends on the specific requirements of the task, availability of data, and the desired robustness of the model against input variations.
