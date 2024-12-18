# Real-Time-Sign-Language-Detection

## Overview

This project demonstrates the use of YOLOv8 for real-time sign language detection. It leverages a custom dataset  to train the model and achieve accurate detection of various sign language gestures.

## Key Features

- **Real-time Detection:** The model processes video frames efficiently, enabling real-time detection of sign language gestures.
- **Accurate Recognition:** Trained on a custom dataset, the model effectively recognizes a range of sign language signs.
- **Compatibility with YOLOv8:** Built using YOLOv8, a state-of-the-art object detection model, for optimal performance.
- **Roboflow Integration:** Leverages Roboflow for dataset management and conversion, streamlining the development process.

## Dataset

- **Source:**  Link to dataset:(https://app.roboflow.com/ds/im3nn3pi4Z?key=CNpQ4IJG4q)
- **Format:** YOLOv8 compatible format 

## Model Architecture

- **YOLOv8:** Employs the YOLOv8 model architecture for object detection.

## Training Process

1. **Dataset Download:** Obtained the dataset from Roboflow in YOLO-v8 format.
3. **Model Training:** Trained the YOLOv8 model on the converted dataset.

## Dependencies

- Python
- PyTorch
- YOLOv8
- Roboflow (for dataset management and dataset)

## Usage

1. Clone this repository.
2. install the ultralytics using this command:
 ```bash
pip install ultralytics
```
3. Run the script named `run.py`

## Results

- Results are stored in result_dir directory. Feel free to check the result. 
- sample predictions are stored in prediction_samples directory

## Project Details 

Check out the following link to see a walkthrough of the project, including a presentation and code explanation.
[Click here!](https://drive.google.com/file/d/10GiG_58dmJlo9rw9eanJQQlkYVg7tNoc/view?usp=drive_link)



