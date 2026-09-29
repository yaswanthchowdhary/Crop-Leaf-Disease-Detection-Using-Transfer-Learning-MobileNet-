🌿 Crop Leaf Disease Detection Using Transfer Learning (MobileNet)
👨‍💻 Author

Yashwanth Chowdary

📌 Project Overview

Crop diseases can significantly affect agricultural productivity and crop quality. This project uses Deep Learning and Transfer Learning to detect diseases from crop leaf images.

A MobileNet-based Convolutional Neural Network (CNN) is trained using transfer learning to classify leaf images into different disease categories.

The trained model can be used through a web application where users upload a crop leaf image and receive the predicted disease.

🚀 Live Demo

🔗 Live Server: https://9m4sld-r4w392awu-arcadawebapps4.vercel.app

Replace YOUR_LIVE_SERVER_URL with your deployed application URL.

✨ Features

🌱 Crop leaf disease detection

🤖 MobileNet Transfer Learning model

📷 Upload leaf images for prediction

📊 Disease classification

⚡ Fast and lightweight model

🌐 Web-based interface

📱 Mobile-friendly model architecture

🧠 Technology Used

Python

TensorFlow / Keras

MobileNet

Transfer Learning

OpenCV

NumPy

Pandas

Flask / Streamlit

HTML & CSS

Jupyter Notebook / Google Colab

📂 Project Structure
Crop-Leaf-Disease-Detection/
│
├── dataset/
│   ├── train/
│   ├── validation/
│   └── test/
│
├── model/
│   └── mobilenet_model.h5
│
├── app.py
├── requirements.txt
├── README.md
└── notebooks/
    └── training.ipynb

🔄 Workflow
Leaf Image
    ↓
Image Preprocessing
    ↓
MobileNet Transfer Learning
    ↓
Feature Extraction
    ↓
Disease Classification
    ↓
Prediction Result

🏗️ Model

This project uses MobileNet as the base architecture.

Transfer learning allows the model to use features learned from a large image dataset and adapt them to crop leaf disease classification.

The final classification layer is customized according to the number of disease classes in the dataset.

⚙️ Installation

Clone the repository:

git clone https://github.com/YOUR_USERNAME/Crop-Leaf-Disease-Detection.git
cd Crop-Leaf-Disease-Detection


Install the required dependencies:

pip install -r requirements.txt

▶️ Run the Application

For Flask:

python app.py


For Streamlit:

streamlit run app.py


Then open the local URL displayed in the terminal.

📸 How to Use

Open the web application.

Upload a crop leaf image.

The image is preprocessed.

The MobileNet model analyzes the image.

The predicted disease is displayed on the screen.

📈 Model Performance

The model performance can be evaluated using:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

Add your actual training and testing accuracy here after completing model evaluation.

🔮 Future Enhancements

Add more crop and disease classes.

Improve model accuracy with data augmentation.

Deploy the application on a cloud server.

Add disease treatment recommendations.

Support real-time camera-based detection.

Optimize the model for mobile devices.

👤 Author

Yashwanth Chowdary

🌱 Crop Leaf Disease Detection using MobileNet and Transfer Learning

⭐ If you find this project useful, consider giving the repository a star!
