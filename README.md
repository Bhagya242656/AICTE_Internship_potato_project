# AICTE_Internship_potato_project
This project uses computer vision to detect diseases in potato leaves, enabling early intervention and improved crop yields.

## Key Features

* Detects common potato leaf diseases such as Early Blight and Late Blight.
* Employs a Convolutional Neural Network (CNN) model, specifically ResNet50, for accurate image classification.  *(Or mention your chosen model)*
* Provides image-based detection for ease of use.

## Getting Started

 * Install requirements:
   pip install -r requirements.txt  # Create requirements.txt: `pip freeze > requirements.txt`

 ## Datasets:
This project utilizes the PlantVillage  dataset, a publicly available resource containing images of various plant leaves, including potato leaves, categorized by disease. 

## Model:
A pre-trained ResNet50 model was fine-tuned on the potato leaf dataset to achieve optimal disease classification accuracy.  

## Usage:
The detect.py script accepts the following command-line arguments:
 * --image path/to/image.jpg:  Path to the image file for disease detection.
 * --video path/to/video.mp4: Path to the video file for disease detection.
 * --camera: Use the webcam for real-time disease detection.
