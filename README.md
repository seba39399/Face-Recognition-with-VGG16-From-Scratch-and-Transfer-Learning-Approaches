# 🧠 Face Recognition with VGG16: From Scratch and Transfer Learning

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Deep Learning](https://img.shields.io/badge/Deep%20Learning-TensorFlow-orange)](https://www.tensorflow.org/)
[![Model](https://img.shields.io/badge/CNN-VGG16-red)](https://keras.io/api/applications/vgg/)

This project implements two face recognition models using the **VGG16** architecture in **TensorFlow/Keras**. It compares a model trained **from scratch** with another using **transfer learning** from **ImageNet**, highlighting differences in accuracy, efficiency, and generalization.

## 🚀 Features
- VGG16 model trained **from scratch**  
- VGG16 model using **transfer learning (ImageNet weights)**  
- Data preprocessing and augmentation  
- Model training, validation, and performance visualization  
- Accuracy and loss comparison between both models  

## 🧰 Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- scikit-learn  

## 📊 Results
Both models achieved strong performance, with the **transfer learning** model showing faster convergence and higher accuracy due to pretrained feature extraction.

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/face-recognition-vgg16.git
   cd face-recognition-vgg16
2. Install dependencies:
   
tensorflow>=2.10.0
keras>=2.10.0
numpy>=1.24.0
matplotlib>=3.7.0
scikit-learn>=1.3.0
opencv-python>=4.8.0

3. Open and run the notebook:

   jupyter notebook Face_Recognition_CNN.ipynb

## 📈 Future Work

 - Extend dataset with more identities

 - Experiment with other CNN architectures (ResNet, EfficientNet)

 - Optimize hyperparameters for higher accuracy

## 📄 Project Author

👨‍💻 Juan Sebastian Peña Valderrama

 - Biomedical Engineer & Artificial Intelligence Specialist. 
 - Radiomics & Imaging Processing Enthusiast.
 - Medical Imaging Analysis Researcher.

📬 Contributions, suggestions, and pull requests are welcome!
