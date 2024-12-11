Sure! Here's a revised version of your README file for the Animal-Species-Prediction repository:

---

# Animal-Species-Prediction
https://colab.research.google.com/drive/1ugpiSjrO1bSc2tjYMLsIfX9CAMTheghb?authuser=3
## Overview
This project uses the YOLOv5 deep learning framework for object detection and classification to develop a system for identifying animal species in real-world images. The project involves collecting and labeling image datasets, training the YOLOv5 model, and integrating the model with a user interface for ease of use.

https://github.com/user-attachments/assets/31e7dcb6-65be-4801-ae7c-284e5de3778b

## Dataset
The dataset used for this project can be found [here](https://drive.google.com/drive/folders/1xBHb2l4Z70Z-oPXHR3QvZF3iaYZnSGx-?usp=sharing). It includes images of various animal species such as:
- Tiger
- Giraffe
- Bear
- Lion
- Elephant
- Deer
- Wolf
- Bull
- Monkey
- Leopard
- Rhinoceros
- Hippo
- Cattle

![pred_cattle](https://github.com/user-attachments/assets/ac37308f-db56-4006-a84a-84c7a566ff71)

![pred_monkey](https://github.com/user-attachments/assets/87c1a867-3e6b-4fe6-873c-50a5f7d0245e)

## Data Preparation
The data preparation process involved collecting image datasets of different animal species and labeling the images with bounding boxes around the animals. This labeling process is necessary for training the YOLOv5 model to accurately detect and classify animal species.

## Data Splitting
The data is split into training and validation sets in an 80:20 ratio. The prepared dataset is uploaded to Google Drive for easy access.

## Model Training
The YOLOv5 model is trained using the following parameters:
- Image size: 415
- Batch size: 31
- Epochs: 100
- Weights: yolov5s

## Inference
Inference is performed using the trained model weights (`best.pt`). The system can detect multiple animal species in the same image and outputs the predicted animal species with corresponding bounding boxes.

## Results
The final animal species detection system accurately identifies animal species in real-world images with a high degree of accuracy. The system can detect multiple animal species in the same image and outputs the predicted animal species with corresponding bounding boxes.

## Conclusion
This project demonstrates the potential of deep learning frameworks like YOLOv5 for object detection and classification in the field of animal species detection. The system developed in this project has practical applications in wildlife conservation, animal behavior studies, and more. The project can be extended to include more animal species and to improve the accuracy and efficiency of the detection system.

## Display
The detected images are displayed with bounding boxes around the identified animal species.
