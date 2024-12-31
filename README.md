
![images](https://github.com/user-attachments/assets/da91c633-8a4d-4df5-bdce-85ff221e63c5)

# Histopathologic Cancer Detection
## Overview
This project aims to classify histopathology images to predict certain characteristics or conditions. It uses deep learning techniques with a ResNet model, applied to a dataset of .tif images.

## Steps in  the Project
1.Data Preparation:

Extracted image IDs from the dataset and ensured consistency by removing .tif extensions where necessary.
Handled missing files by filtering them out during dataset loading.

2.Model Training:

Used a pre-trained ResNet model as the backbone.
Optimized training with hyperparameters such as learning rate, batch size, and optimizer choice.

3.Testing Phase:

Implemented a custom dataset class (HistopathologyDataset) to handle test images and gracefully skip missing files.
Predicted probabilities using the trained model and converted them into binary classifications.

4.Result Submission:

Generated a CSV file containing image IDs and predictions for submission.
