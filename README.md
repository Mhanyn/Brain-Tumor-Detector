# Brain-Tumor-Detector
CNN-Based Diagnosis of Brain Tumors
This repository contains the code and data for a research project on using Convolutional Neural Networks (CNNs) to diagnose brain tumors from MRI scans. The project investigates the effectiveness of various CNN architectures, including a custom-designed model and pre-trained models (DenseNet201 and Xception), for classifying brain MRI scans into four categories: Glioma, Meningioma, Pituitary, and Healthy.

## Abstract

Every year, thousands of lives are tragically affected by the late or misdiagnosis of brain tumors. The consequences—delayed treatment, reduced survival rates, and diminished quality of life—are devastating. This research presents a potential solution: a highly accurate deep learning model designed to revolutionize brain tumor diagnosis and dramatically improve patient outcomes.

## Methodology

The project followed a multi-phase approach:

1. **Data Acquisition and Preprocessing:**  A dataset of 7023 brain MRI scans was utilized, categorized into four tumor types. Data augmentation and normalization techniques were employed to improve model robustness.
2. **Model Development:** Four CNN architectures were implemented:
    * A custom-designed CNN optimized for brain tumor classification.
    * Fine-tuned pre-trained models (DenseNet201 and Xception).
3. **Model Training and Evaluation:** Models were trained using the Adam optimizer and evaluated using various metrics, including accuracy, precision, recall, F1-score, and loss. Confusion matrices and ROC curves were generated for detailed performance analysis.

## Results

The custom-designed CNN model significantly outperformed the pre-trained models, achieving a test accuracy of 99.25%. The superior performance is attributed to its tailored architecture and the incorporation of pixel intensity analysis. Detailed results, including confusion matrices, ROC curves, and F1-scores for each class are presented in the code.


## Code Structure

The code is organized into the following directories:

* `data`: Contains the preprocessed MRI data.
* `models`: Contains the implementation of the different CNN architectures.
* `utils`: Contains helper functions for data preprocessing, visualization, and evaluation.
* `results`: Contains the experimental results, including confusion matrices and ROC curves.
* `training`: Contains the training scripts.

## Requirements

* Python 3.x
* TensorFlow/Keras (or PyTorch)
* NumPy
* Scikit-learn
* Matplotlib

## License

