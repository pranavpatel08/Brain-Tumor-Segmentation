# U-Net for Brain Tumor Detection in MRI Scans
This assignment was created as part of my role as a Teaching Assistant (TA) for the Deep Learning (CS 7150) course at Northeastern University. The project aims to provide students with hands-on experience using U-Net, a deep learning architecture widely used for image segmentation tasks. In this assignment, students work on automatically detecting and outlining brain tumors in MRI scans, improving the accuracy of tumor boundary identification.

### Key Features:
* **U-Net Architecture**: Built and trained a U-Net model for segmenting brain tumors in MRI images.
* **MRI Data Types**: Evaluated the model across various MRI scan types (T1, T1CE, T2, FLAIR), considering the unique characteristics of each scan type.
* **Performance Metrics**: Tested different technical approaches and performance measures to determine the most effective configuration for segmenting diverse tissue types and tumor structures.

### Dataset:
This project uses the [BraTS 2020 Training Data](https://www.kaggle.com/datasets/awsaf49/brats2020-training-data), which provides MRI scans with tumor annotations. The dataset includes various types of MRI images (T1, T1CE, T2, FLAIR) for training the U-Net model to detect and segment brain tumors.

### Objective:
To understand and apply U-Net for medical image segmentation, this project serves as a tutorial for students to implement, experiment, and optimize a deep learning model for real-world medical imaging tasks.

### How to Use:
1. Clone this repository.
2. Download the ([BraTS 2020 Training Data](https://www.kaggle.com/datasets/awsaf49/brats2020-training-data) and set up the dataset.
3. Follow the provided instructions to preprocess MRI data and set up the U-Net architecture.
4. Train the model on your dataset and evaluate performance with provided metrics.
5. Experiment with different MRI scan types and configurations for improved results.
