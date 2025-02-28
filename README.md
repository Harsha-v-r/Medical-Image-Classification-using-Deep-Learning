**Medical Image Classification using Deep Learning**
This project focuses on detecting pneumonia from chest X-ray images using deep learning and machine learning techniques.

**🚀 Technologies Used**
Deep Learning: ResNet50 (Transfer Learning)
Machine Learning: Random Forest Classifier
Libraries: TensorFlow, Keras, OpenCV, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
Evaluation Metrics: Accuracy, Precision, Recall, F1-Score
**📂 Dataset**
The dataset consists of labeled chest X-ray images for pneumonia detection.

**# Paths to the dataset (Replace with your system's path)**
TRAIN_DIR = r"/path/to/chest_xray/train"
TEST_DIR = r"/path/to/chest_xray/test"
**🛠 Preprocessing & Model Training**
Resized images to 224x224 pixels.
Normalized pixel values to scale [0, 1].
Augmented images using ImageDataGenerator.
Trained a ResNet50 model with GlobalAveragePooling2D for feature extraction.
**📊 Model Performance**
Evaluated using confusion matrix, precision, recall, and F1-score.
Applied RandomForestClassifier for additional classification.
**🔥 Results**
Achieved high accuracy in classifying normal vs. pneumonia cases.
Robust deep learning pipeline for medical image analysis.
