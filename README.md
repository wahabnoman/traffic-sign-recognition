🚦 Traffic Sign Recognition (GTSRB Dataset)
This project uses Deep Learning to classify German traffic signs from the GTSRB Dataset.

📌 Features
Image preprocessing: resizing and normalization for CNN input

Model: Convolutional Neural Network (CNN) built using TensorFlow/Keras

Visualization: Accuracy plots & confusion matrix

High Accuracy: Achieved ~99% validation accuracy

📂 Dataset
The dataset used is the German Traffic Sign Recognition Benchmark (GTSRB) from Kaggle:
🔗 https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign?resource=download

🛠 Installation
Clone this repository:
git clone https://github.com/YOUR_USERNAME/traffic-sign-recognition.git
cd traffic-sign-recognition
Install dependencies:
pip install -r requirements.txt
Download & place dataset inside data/ folder:
data/
├── Train/
├── Test/   (optional)

🚀 Usage
Train the model
python traffic_sign_recognition.py
Load and use trained model
from tensorflow.keras.models import load_model
model = load_model("model.h5")
predictions = model.predict(new_images)

📊 Results
Validation Accuracy: ~99.46%

Confusion Matrix:
The model performs exceptionally well across all traffic sign classes.

