# Retina Blood Vessel Segmentation using U-Net

This repository is part of the homework assignment for a deep learning course, focusing on medical image segmentation. Specifically, it implements the U-Net architecture in Python using TensorFlow or PyTorch to segment retinal blood vessels from fundus images.

## Repository Contents

- `hw3_2layers.ipynb`: A U-Net model with 2 convolutional layers, including normalization.
- `hw3_2layers_wonorm.ipynb`: A U-Net model with 2 convolutional layers, without normalization.
- `hw3_3layers.ipynb`: An extended U-Net model with 3 convolutional layers, with normalization.
- `hw3_3layers_wonorm.ipynb`: A 3-layer U-Net model without normalization.
- `hw3_4layers.ipynb`: A deeper U-Net model with 4 convolutional layers, with normalization.
- `hw3_4layers_wonorm.ipynb`: A 4-layer U-Net model without normalization.
- `hw3_report.pdf`: Comprehensive report document detailing the approach, experiments, and outcomes of the segmentation task.

## Project Description

In this assignment, students are expected to deepen their understanding of Convolutional Neural Networks (CNNs) by constructing and training a U-Net architecture. The key learning outcomes include:

- Gaining hands-on experience with the training and testing of medical image segmentation models.
- Comprehending the U-Net architecture and how to piece together each layer using TensorFlow or PyTorch.
- Learning to calculate performance metrics such as the Dice score and Intersection over Union (IoU) score.

### Data Overview

The dataset consists of X high-resolution retinal fundus images, each accompanied by pixel-level ground truth annotations for blood vessel segmentation. This dataset plays a crucial role in promoting research in medical image analysis and supports the diagnosis and treatment of various retinal vascular diseases.

## How to Use

To use these notebooks:

1. Clone the repository.
2. Install the required libraries (TensorFlow or PyTorch).
3. Download the dataset from the provided canvas homework 3 link.
4. Run the notebooks in sequence to train and test the U-Net models.
5. Evaluate the models using the included performance metrics.

## Authors

* **Ameya Deshmukh** - *Initial work* - [ameya1252](https://github.com/ameya1252)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

