# License-Plate-Recognition-ML
"A deep learning-based license plate recognition system using OpenCV and TensorFlow."

# License Plate Recognition Model 🚗🔍  

A deep learning-based system for recognizing vehicle license plates using OpenCV and TensorFlow. This project is trained on a dataset of license plate images and can detect and extract plate numbers from images or video streams.  

## 📌 Features  
✅ Detects license plates from images and videos  
✅ Uses OpenCV for image processing  
✅ Trained using CNN-based deep learning model  
✅ Supports real-time detection  

## 🛠️ Tech Stack  
- Python 🐍  
- OpenCV 🖼️  
- TensorFlow/Keras 🤖  
- NumPy & Pandas 📊  

## 🚀 How to Run  
1. Clone this repository:  
git clone https://github.com/ShivKhurana11/License-Plate-Recognition-ML

2. Install dependencies:
   pip install -r requirements.txt 

3. Run the model:
   python detect_plate.py

   ## 📂 Dataset & Model
This project uses OpenCV's **Haar Cascade Classifier** for license plate detection.  
- Pre-trained XML file: [haarcascade_russian_plate_number.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_russian_plate_number.xml)  
- You can also train your own model using OpenCV's Cascade Trainer.  

