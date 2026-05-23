# DermaAI – AI-Powered Skin Disease Detection System

DermaAI is an AI-powered dermatology assistance system designed for early skin disease detection using deep learning and computer vision. The application analyzes skin images, predicts possible skin conditions, provides confidence-based results, and offers safe preliminary guidance through a rule-based support module.

> Built as an end-to-end healthcare AI project combining deep learning, image processing, and user-focused healthcare assistance.

---

## Features

- Skin disease prediction from uploaded dermatological images
- Deep learning-based image classification
- CNN, Siamese CNN, and EfficientNet model experimentation
- Transfer learning and fine-tuning for improved performance
- Image preprocessing and augmentation pipeline
- Confidence-based prediction output
- Multimodal architecture support (image + structured data)
- Safe rule-based recommendation system
- Interactive healthcare assistance concept

---

## Tech Stack

### Languages
- Python

### Deep Learning / ML
- TensorFlow
- Keras
- NumPy
- Pandas
- Scikit-learn

### Computer Vision / Image Processing
- OpenCV
- PIL / Image Processing Utilities

### Model Architectures
- Custom CNN
- Siamese CNN
- EfficientNet
- Transfer Learning
- Feature Fusion Models

### Development Environment
- Jupyter Notebook
- Google Colab / Local Training

---

## Project Architecture

The system follows a structured AI pipeline:

```text
Input Skin Image
      ↓
Image Preprocessing
(Resize, Normalize, Augmentation)
      ↓
Feature Extraction
(CNN / EfficientNet / Siamese Architecture)
      ↓
Classification Layer
      ↓
Confidence Score Generation
      ↓
Rule-Based Guidance / Recommendations
      ↓
Final Output
```

---

## Model Details

This project explores multiple deep learning architectures for comparative performance analysis:

### 1. Custom CNN
A convolutional neural network built for dermatological image classification.

- Conv2D Layers
- ReLU Activation
- MaxPooling
- Flatten Layer
- Dense Layers
- Dropout Regularization
- Softmax Output

---

### 2. Siamese CNN
Used for similarity-based feature learning and comparative classification.

- Twin CNN branches
- Shared weights
- Distance-based feature comparison
- Enhanced representation learning

---

### 3. EfficientNet
Transfer learning architecture used for improved performance.

- Pretrained backbone
- Fine-tuning
- Efficient scaling
- Better generalization

---

## Dataset

The model is trained using dermatological image datasets including:

- **SCIN (Skin Condition Image Network)**
- Public skin disease datasets for experimentation

Dataset preprocessing includes:

- Image resizing
- Pixel normalization
- Data augmentation
- Batch generation
- Multi-image input handling

---

## Evaluation Metrics

Model performance was evaluated using:

- Accuracy
- Top-1 Accuracy
- Top-3 Accuracy
- Top-5 Accuracy
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

---

## Training Optimizations

Implemented optimization strategies include:

- Adam Optimizer
- Early Stopping
- Model Checkpointing
- Learning Rate Scheduling
- Dropout Regularization
- Batch Normalization

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/DermaAI.git
cd DermaAI
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

Run the Jupyter notebook:

```bash
jupyter notebook
```

Open:

```bash
SCIN_Model.ipynb
```

Train the model or run predictions using sample input images.

---

## Project Structure

```text
DermaAI/
│
├── SCIN_Model.ipynb
├── dataset/
├── models/
├── outputs/
├── images/
├── requirements.txt
└── README.md
```

---

## Future Improvements

- Web application deployment
- Mobile application integration
- Real-time camera-based detection
- Explainable AI (Grad-CAM / attention maps)
- Doctor consultation integration
- Cloud deployment
- Larger dermatology datasets
- Multi-language support

---

## Disclaimer

This project is developed for educational and research purposes only.

DermaAI does **not** replace professional medical diagnosis or treatment. Predictions are intended as preliminary assistance only.

---

## Author

**Rohith Cherukuri**

Computer Science Engineering (Data Science)  
AI / Machine Learning Enthusiast

---

## License

This project is open-source and available under the MIT License.
