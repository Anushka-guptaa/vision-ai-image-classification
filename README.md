# Vision-AI-Image-Classification
A comprehensive 5-day deep learning bootcamp focusing on end-to-end *computer vision pipeline* for classifying images using *Convolutional Neural Networks (CNNs)* and *Transfer Learning (MobileNetV2)*, trained on the MNIST, CIFAR-10 and Cats vs Dogs datasets.
The project demonstrates a complete AI workflow — from data preprocessing and augmentation to model evaluation and visualisation(ROC curve, confusion matrix, training curves) — built in Python using TensorFlow/Keras.
## Project Overview
This project explores image recognition using Convolutional Neural Networks across three different datasets:
- *MNIST*: Handwritten digit recognition
- *CIFAR-10*: Object classification (10 categories)
- *Cats vs Dogs*: Binary image classification

It covers:

* Loading and preprocessing datasets (normalisation, reshaping, augmentation)
* Exploratory Data Analysis (EDA) 
* Training a custom CNN model
* Enhancing performance with Transfer Learning using MobileNetV2
* Evaluating with multiple metrics like using Accuracy, Precision, Recall, F1-score, ROC-AUC
* Visualising results using training curves, confusion matrix, and ROC-AUC curve
* Sample predictions on test images

## 🗂 Datasets

### 1. MNIST Dataset
- *Source*: Kaggle
- *Description*: 70,000 grayscale images of handwritten digits (0-9)
- *Image Size*: 28x28 pixels
- *Classes*: 10 (digits 0-9)

### 2. CIFAR-10 Dataset
- *Source*: Kaggle
- *Description*: 60,000 colour images in 10 classes
- *Image Size*: 32x32 pixels
- *Classes*: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck

### 3. Cats vs Dogs Dataset
- *Source*: Kaggle
- *Description*: Binary classification dataset with cat and dog images
- *Classes*: 2 (cats and dogs)

## 🛠 Technologies & Libraries

- *Development Environment*: Google Colab
- *Deep Learning Framework*: TensorFlow/Keras
- *Data Visualization*: Matplotlib
- *Data Processing*: NumPy, Pandas

## 📊 Model Configuration

- *Training Epochs*: 5-10 epochs per model
- *Architecture*: Convolutional Neural Networks (CNN)
- *Optimisation*: Various optimisers (Adam, SGD, etc.)
- *Loss Functions*: Categorical/Binary Crossentropy

## 📁 Project Structure
cnn-image-recognition-bootcamp/
├── notebooks/
│   ├── Day_1_MNIST_Recognition
│   ├── Day_2_CIFAR10_Classification
│   ├── Day_3_Cats_vs_Dogs
│   ├── Day_4_Model_Comparison
│   └── Day_5_Final_Project
├── results/
│   ├── plots/
│   ├── model_metrics/
│   └── visualisations/
├── datasets/
│   └── (Downloaded directly in Google Colab)
└── README.md

## 🚀 Getting Started

### Access the Project

1. *Open Google Colab*
   - Navigate to [Google Colab](https://colab.research.google.com/)
   - Sign in with your Google account

2. *Load the notebooks*
   - Upload the .ipynb files to your Google Drive
   - Open notebooks directly in Colab
   - Or clone this repository and open notebooks from GitHub

3. *Dataset Access*
   - Datasets are downloaded directly within the Colab notebooks using Kaggle API
   - Ensure you have a Kaggle account for dataset access
   - Required datasets:
     - [MNIST Dataset](https://www.kaggle.com/datasets/hojjatk/mnist-dataset)
     - [CIFAR-10 Dataset](https://www.kaggle.com/datasets/cifar10)
     - [Cats vs Dogs Dataset](https://www.kaggle.com/datasets/salader/dogs-vs-cats)


## 📈 Training Results

### Model Performance Summary

| Dataset      | Epochs | Training Accuracy| Validation Accuracy | Loss |
|--------------|--------|------------------|---------------------|------|
| MNIST        | 5-10   | ~99%             | ~98%                | ~0.04|
| CIFAR-10     | 5-10   | ~69%             | ~72%                | ~0.79 |
| Cats vs Dogs | 5-10   | ~80%             | ~79%                | ~0.54 |

## 📊 Visualizations

The project includes comprehensive visualisations using Matplotlib:
- Training/Validation accuracy curves
- Loss curves
- Sample predictions
- Confusion matrices
- Filter visualisations

## 📚 Learning Outcomes & Skills Developed

By the end of this 5-day bootcamp, I developed expertise in:

### 🔧 Technical Skills
- *Image preprocessing and augmentation*: Data normalisation, resizing, rotation, flipping, and other augmentation techniques
- *Deep learning fundamentals and CNN architecture*: Understanding convolutional layers, pooling, activation functions, and network design
- *Model training, evaluation, and optimisation*: Hyperparameter tuning, loss functions, optimisers, and performance metrics
- *Visualisation of results and metrics*: Creating insightful plots for training curves, confusion matrices, and model interpretability

### 💼 Professional Skills
- *Collaboration and documentation best practices*: Version control, code organisation, and comprehensive project documentation
- *Showcasing ML projects for recruiters*: Portfolio development, technical presentation, and industry-relevant project structure

### 🎯 Core Competencies Gained
- End-to-end machine learning pipeline development
- Multi-dataset comparison and analysis
- Performance benchmarking across different image recognition tasks
- Industry-standard deep learning workflows

## 🎯 Key Features

- ✅ Implementation of CNN models for three different datasets with Image preprocessing & normalization
- ✅ Comprehensive data visualisation and analysis of training curves, confusion matrix, ROC-AUC curve and accuracy comparison chart
- ✅ Model performance comparison
- ✅ Data augmentation (rotation, flipping, scaling)
- ✅ Model evaluation (Accuracy, Precision, Recall, F1-score, ROC-AUC)
- ✅ Training progress visualisation

## 🤝 Contributing

Contributions are welcome!  

To contribute:  
1. **Fork** the repository  
2. **Create** your feature branch (`git checkout -b feature/AmazingFeature`)  
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)  
4. **Push** to the branch (`git push origin feature/AmazingFeature`)  
5. **Open** a Pull Request  

Please ensure that your changes adhere to the existing style and include relevant documentation or tests as needed.


## 🙏 Acknowledgments

- Kaggle for providing the datasets
- TensorFlow/Keras team for the excellent deep learning framework
- The deep learning community for tutorials and resources

## 📬 Contact

*Anushka Gupta*
[GitHub](https://github.com/Anushka-guptaa) | [LinkedIn](https://www.linkedin.com/in/anushka-gupta-7621a6298/)

------
