# CNN Footwear Classifier (Shoes, Sandals, & Boots)

A Convolutional Neural Network (CNN) model built with TensorFlow/Keras to classify footwear images into three categories: shoes, sandals, and boots. This project was created as a submission for a Dicoding machine learning course.

## 📜 About The Project

The primary goal of this project is to build and train a robust deep learning model for classifying images of different types of footwear. It demonstrates a complete workflow for a computer vision task, starting from data preparation and augmentation to building, training, and saving a CNN model.

## ✨ Features

* **Data Pipeline**: Utilizes `ImageDataGenerator` for efficient data loading and real-time image augmentation to improve model generalization.
* **CNN Architecture**: Implements a `Sequential` model in Keras with multiple `Conv2D` and `MaxPooling2D` layers for hierarchical feature extraction.
* **Model Training**: The model is trained and validated to ensure high accuracy on unseen data.
* **Model Portability**: Includes steps to save the trained model in both SavedModel format and as a `.tflite` file, making it ready for deployment on various platforms, including mobile and web (indicated by the `tensorflowjs` dependency).

## 🚀 Getting Started

### Prerequisites

Ensure you have Python 3 installed. It is highly recommended to use a virtual environment to manage dependencies.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/irgidev/cnn-footwear-classifier.git](https://github.com/irgidev/cnn-footwear-classifier.git)
    cd cnn-footwear-classifier
    ```

2.  **Download the dataset:**
    *(Catatan: Anda perlu menyediakan link ke dataset Anda, misalnya dari Google Drive atau sumber lain).*
    The "Shoe vs Sandal vs Boot" dataset is required to run this project. Download it from the link below and extract it into the project's root directory.

    ➡️ **[Link untuk Mengunduh Dataset Anda di Sini]**

3.  **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

### Usage

1.  Open the `dicoding_classification_submission.ipynb` notebook using Jupyter Notebook or Google Colab.
2.  Verify that the dataset path within the notebook correctly points to the extracted folder.
3.  Run the cells sequentially to perform data loading, model training, and evaluation.

## ⚙️ Dependencies

* TensorFlow
* NumPy
* Matplotlib
* scikit-learn
* TensorFlowJS (for model conversion)

A complete list of specific versions can be found in the `requirements.txt` file.

## 🎓 Dicoding Submission

This project was submitted to fulfill the requirements of a machine learning course at Dicoding Academy.

---