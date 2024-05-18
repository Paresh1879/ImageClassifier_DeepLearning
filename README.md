# Image Classifier

## Overview

This project aims to develop an image classifier capable of distinguishing between two categories of any image: Here, I have taken "pets" and "wildlife" as the two categories. It utilizes TensorFlow for building and training the classifier model. The classifier is designed to handle image data in the JPEG, JPG, BMP, and PNG formats.
## Installation

To run the image classifier, you'll need to have TensorFlow, TensorFlow GPU, OpenCV, and Matplotlib installed. You can install these dependencies using pip:

```bash
pip install tensorflow tensorflow-gpu opencv-python matplotlib
```

## Usage

1. **Data Preparation**: Organize your image data into two categories and place them in separate directories within a main directory named `Images`.

2. **Data Preprocessing**: Remove any uncertain images (e.g., corrupted or unsupported formats) from the dataset using the provided script.

3. **Training the Model**: Execute the Jupyter Notebook `Image Classifier.ipynb` to load and preprocess the image data, build, train, and evaluate the classifier model.

4. **Testing**: Once the model is trained, you can test it using new images. 
