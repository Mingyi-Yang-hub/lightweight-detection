# lightweight-detection
This work is a lightweight network for detecting free fluid in FAST examinations to screen for internal hemorrhage.

The network is built upon the general and lightweight object detection architecture YOLOx, with key structural optimizations applied to both its backbone and neck components through a Dual‑Stream Fusion backbone and a Global Fusion Feedback neck, enhancing both feature extraction and multi‑scale fusion efficiency. 

# Dataset
This model was trained on a private dataset, which consists of ultrasound images of rabbits with active liver tissue hemorrhage.

# Code
Code is developed based on the publicly available library MMDetection released by OpenMMLab. It leverages its established frameworks and pipelines for training, testing, and data loading, while implementing the proposed model on this foundation.
The code of proposed model will be released soon.
