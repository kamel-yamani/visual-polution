# Visual Polution
The goal of this project is to develop a visual pollution detection and classification system. The system is trained on the provided dataset of images of various forms of pollution (e.g. garbage, graffiti etc). The custom dataset is used to fine-tune a pre-trained YOLOv5 model, which is a state-of-the-art object detection model, to improve its accuracy in detecting and classifying different forms of pollution.

The project is divided into several stages:
1. Data pre-processing: The dataset is pre-processed to ensure that it is in the correct format for the YOLOv5 model and to improve the performance of the model.
2. Transfer learning: The pre-trained YOLOv5 model is fine-tuned on the custom dataset to adapt it to the task of pollution detection and classification. The YOLOV5 model is first initialized with the pre-trained weights (from the COCO dataset, which contained 1.2 million targets in 80 categories) eliminating the need for random initialization. The model is then trained for 200 epochs in order to be fine-tuned and more adapted to our task.
3. Model evaluation: The fine-tuned model is evaluated on a held-out test set to measure its performance in detecting and classifying different forms of pollution. it

The system will be able to detect and classify different forms of pollution in real-time and can be used for monitoring and enforcement of environmental regulations. The system can also be used to track the progress of cleanup efforts and identify areas that need more attention.
