 Brain Tumor Classification using Deep Learning

This project applies **five different classifiers** to detect and classify brain tumors from MRI images.  
The models are trained and evaluated on a public Kaggle dataset.
The best model VGG has a gardio interface where you can keep an MRI image and get the result as the tumor type or no tumor.
---

##  Dataset
We used the **Brain Tumor MRI Dataset** available on Kaggle:  
 [Brain Tumor MRI Datasets](https://www.kaggle.com/datasets/luluw8071/brain-tumor-mri-datasets)

The dataset contains MRI images labeled by tumor type and non-tumor cases.

---

##  Models Implemented
The following deep learning models were trained and compared:

1. AlexNet  
2. MobileNet  
3. VGG16
4. LSTM
5. Inception

Each model was fine-tuned and evaluated for classification accuracy, precision, recall, and F1 score.


## Features
- Preprocessing of MRI images (resizing, normalization, augmentation).  
- Implementation of five different deep learning classifiers.  
- Comparison of performance metrics across models.  
- Visualization of training/validation accuracy and loss.  

---

##  Results
- The project highlights which model performs best on the dataset.  
- Detailed performance metrics and plots are included in the notebooks.  
