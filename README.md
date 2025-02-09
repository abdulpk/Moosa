🌿 Cotton Crop Prediction using Deep Learning

This repository contains a deep learning-based cotton crop disease prediction model. The model leverages TensorFlow and Keras to classify cotton crop images based on various disease conditions. It uses a Convolutional Neural Network (CNN) for image classification.

📌 Features

Deep Learning Model: Implements a CNN using TensorFlow/Keras.
Image Processing: Loads and preprocesses images from the dataset.
Model Training: Uses Precision, Recall, and Confusion Matrix for performance evaluation.
Visualization: Includes training history and performance metrics.

 🛠 Installation & Setup
 
Clone the repository
git clone https://github.com/abdulpk/Moosa.git
cd Moosa
Install dependencies
pip install Jupyter notebook
Run the Jupyter Notebook
jupyter notebook

📊 Dataset

The dataset contains cotton crop images classified into:
The dataset analysed during the current study are available in the "Cotton Plant Disease" dataset, https://www.kaggle.com/datasets/dhamur/cotton-plant-disease/data
Aphids
Army worm
Bacterial Blight
Powdery Mildew
Target spot
Healthy
If not included, download it and place it in the dataset/ directory.

🏗 Model Details

Uses a Convolutional Neural Network (CNN) for classification.
Image Size: 256x256 pixels.
Batch Size: 32.
Epochs: 20.

🔥 Training Process

The dataset is loaded using tf.keras.preprocessing.image_dataset_from_directory.
The model is trained using categorical cross-entropy loss.
Evaluation metrics include:
Precision, Recall, Confusion Matrix

📈 Results & Performance

Confusion matrix and classification report visualize model performance.
Graphs show loss/accuracy trends over epochs.
🔍 Future Enhancements
Improve accuracy by fine-tuning pre-trained models (e.g., ResNet, VGG16).
Data Augmentation to enhance generalization.
Integration of real-time image classification.

🤝 Contribution

Contributions are welcome! If you find any issues or want to improve the model, feel free to open a pull request.

📩 Contact
For any questions or collaborations, reach out via GitHub Issues.
