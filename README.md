# Yolo-helpers
This repository contains a Jupyter Notebook `helpers.ipynb` that includes various helper functions for training object detection models using YOLO (You Only Look Once) architecture.

YOLO is a state-of-the-art object detection system that is widely used in computer vision applications. This notebook provides a collection of helper functions that will be useful for computer vision engineers who are working with YOLO.

## Features
This notebook includes the following helper functions:
- split_data: This function can be used to split the data to train and test folder and genrate a txt files for both train and test files , which can be used in yaml file for training purposes.
- image_preprocessing: This function is used to preprocess images for YOLO training. It includes resizing the images, converting them to the appropriate format, and normalizing the pixel values.
- annotation_parser: This function is used to parse annotation files and extract the bounding box information for each object in the image.
- generate_anchors: This function is used to generate anchor boxes for YOLO.
- evaluate: This function is used to evaluate the performance of the YOLO model on a given dataset.
- draw_boxes: This function is used to draw the predicted bounding boxes on an image.
- crop_image: This function helps to crop the image at the roi provided.
- create_class_names_file: This function helps to create the class_names.txt files for training purposes.
## Contributing
If you have any suggestions for additional helper functions that could be included in this notebook, please feel free to contribute. You can submit a pull request with your changes, and I will review them as soon as possible.

## Compatibility
These helper functions are compatible with all versions of YOLO.

# Installation
To use these helper functions, simply download the helpers.ipynb file and run it in a Jupyter Notebook environment. No additional installation is required.

# License
This repository is licensed under the MIT License. Please see the LICENSE file for more information.

* Remember, with great YOLO power comes great object detection responsibility!