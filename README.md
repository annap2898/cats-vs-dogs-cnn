\# Cats vs Dogs – Convolutional Neural Network



A deep learning project for binary image classification using a Convolutional Neural Network (CNN) built with \*\*TensorFlow\*\* and \*\*Keras\*\*.



---



\## Overview

This project aims to classify images of cats and dogs using a CNN model trained on the popular \*\*Kaggle Cats vs Dogs dataset\*\*.  

It demonstrates image preprocessing, data augmentation, model design, training, evaluation, and visualization of results.



---



\## Model \& Methodology

\- \*\*Architecture:\*\* Sequential CNN with Conv2D, MaxPooling, Dense, Dropout, and BatchNormalization layers.  

\- \*\*Optimizer:\*\* Adam with learning rate reduction on plateau.  

\- \*\*Callbacks:\*\* EarlyStopping, ReduceLROnPlateau, and ModelCheckpoint for stable and efficient training.  

\- \*\*Data Processing:\*\* ImageDataGenerator for image augmentation and normalization.



---



\## Tech Stack

\- Python  

\- TensorFlow / Keras  

\- Matplotlib  



---



\## Results

\- Validation Accuracy: ~97%  

\- Training: 10 epochs on 25,000 images (cats \& dogs)  

\- Environment: Google Colab (GPU enabled)  



Example training curves:  

\*(add a plot.png here if you have one!)\*



---



\## Installation

Clone the repository and install dependencies:

```bash

git clone https://github.com/annap2898/cats-vs-dogs-cnn.git

cd cats-vs-dogs-cnn

pip install -r requirements.txt



