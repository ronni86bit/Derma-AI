# DermaAI – AI-Powered Skin Disease Detection System

DermaAI is an AI-powered dermatology assistance system designed for early skin disease detection using deep learning and computer vision. The system analyzes skin images, predicts possible skin conditions, provides confidence-based results, and offers safe preliminary guidance.

This project demonstrates the practical application of AI in healthcare by combining image classification, deep learning architectures, and structured diagnostic assistance.

---

## Project Overview

Skin diseases are among the most common health concerns worldwide, but access to dermatological consultation is often limited. DermaAI addresses this gap by providing an AI-assisted solution for early-stage skin condition identification using medical image analysis.

Users can provide skin images, and the model predicts the most likely condition using trained deep learning architectures.

---

## Features

- AI-powered skin disease prediction
- Deep learning-based dermatological image classification
- Confidence score prediction
- CNN-based feature extraction
- EfficientNet transfer learning implementation
- Siamese CNN experimentation
- Image preprocessing and augmentation pipeline
- Multi-model comparative experimentation
- Rule-based recommendation support
- End-to-end implementation in Jupyter Notebook

---

## Notebook Included

This repository directly contains the complete Jupyter Notebook implementation.

The notebook includes:

- Complete dataset loading pipeline
- Data preprocessing
- Image normalization
- Data augmentation
- Model architecture definitions
- CNN implementation
- Siamese network implementation
- EfficientNet transfer learning setup
- Training configuration
- Hyperparameter setup
- Model training
- Validation workflow
- Performance evaluation
- Metrics calculation
- Prediction logic
- Experimental comparisons

No separate source code files are required — everything is documented inside the notebook.

---

## Tech Stack

### Programming Language
- Python

### Libraries & Frameworks
- TensorFlow
- Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Scikit-learn
- PIL
- Jupyter Notebook

---

## Deep Learning Architectures Used

### Custom CNN
A convolutional neural network designed for skin disease classification.

Architecture includes:
- Conv2D layers
- ReLU activation
- MaxPooling
- Flatten layers
- Dense layers
- Dropout regularization
- Softmax classification

---

### Siamese CNN
Used for similarity learning and comparative feature extraction.

Features:
- Shared convolutional branches
- Distance-based comparison
- Improved representation learning

---

### EfficientNet
Transfer learning model for optimized classification performance.

Features:
- Pretrained backbone
- Fine-tuning
- Efficient scaling
- Better generalization

---

## Dataset

This project uses dermatological image datasets including:

- SCIN (Skin Condition Image Network)
- Additional skin disease image datasets used during experimentation

Dataset-related preprocessing includes:
- Image resizing
- Normalization
- Augmentation
- Batch generation
- Label encoding

Detailed dataset workflow is available inside the notebook.

---

## Evaluation Metrics

Performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Top-1 Accuracy
- Top-3 Accuracy
- Top-5 Accuracy
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

---

## Training Optimizations

Implemented optimizations include:

- Adam Optimizer
- Early Stopping
- Dropout
- Batch Normalization
- Transfer Learning Fine-Tuning
- Model Checkpointing

---

## Repository Structure

```bash
DermaAI/
│
├── DermaAI.ipynb
├── README.md
```

The notebook contains the complete source code and workflow.

---

## How to Run

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/DermaAI.git
cd DermaAI
```

### 2. Install Dependencies

```bash
pip install tensorflow keras numpy pandas opencv-python matplotlib scikit-learn pillow
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open Notebook

Open:

```bash
DermaAI.ipynb
```

Run cells sequentially.

---

## Future Improvements

- Web deployment
- Mobile app integration
- Real-time camera detection
- Explainable AI (Grad-CAM)
- Doctor consultation integration
- Cloud deployment
- Multi-language support
- Clinical validation

---

## Disclaimer

This project is developed for educational and research purposes only.

It is not intended to replace professional medical diagnosis or treatment.

---

## Author

**Rohith Cherukuri**  
B.Tech CSE (Data Science)  
AI / Machine Learning Enthusiast
