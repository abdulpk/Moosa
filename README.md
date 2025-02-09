Cotton Crop Monitoring and Prediction: PlusCal, TLA+, and CNN Based Method

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


🌿 Cotton Crop Management using TLA+

This repository contains a formal verification model for cotton crop health management, designed using TLA+ and PlusCal. The module implements an automated decision-making system that evaluates disease symptoms, growth stages, and pest risks based on provided inputs. The PlusCal algorithm helps in systematically identifying the most likely disease, optimal growth stage, and critical pest threat, ensuring data-driven agricultural decision-making.

📌 Features

Disease Diagnosis: Matches observed symptoms with known diseases.
Growth Stage Evaluation: Identifies the best growth stage for cotton crops.
Pest Risk Assessment: Determines the most critical pest based on growth conditions.
TLA+ Formal Verification: Ensures correctness in disease prediction and crop phase transitions.

Install TLA+ Toolbox
Download from: TLA+ GitHub
Run Model Checking
Open cottoncropoverall.tla in TLA+ Toolbox and execute the model checker.

🔬 TLA+ Verification
Ensures logical consistency in disease, growth stage, and pest assessments.
Verifies requirement properties, such as:
Symptom-based disease classification.
Growth stage matching for optimal yield.
Pest impact assessment for crop protection.

🏆 Future Enhancements
Extend to real-time data inputs.
Integrate climate and soil condition factors.
Apply machine learning for dynamic rule optimization.

📩 Contact
For any questions or collaborations, reach out via GitHub Issues.
