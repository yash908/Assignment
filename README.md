📌 Problem Statement Summary

The assignment consists of three main tasks:

Zero-shot object detection
Use the first image and its corresponding ground-truth mask for each object to initialize SAM2 and detect the same object in all other images of that category.

Mask to bounding box conversion
Convert the segmentation masks output by SAM2 into tightly fitting bounding boxes.

Performance evaluation
Compare predicted bounding boxes with ground-truth bounding boxes extracted from masks and compute object detection performance (IoU per object).

📂 Dataset

Dataset: CMU10_3D

Directory used: data_2D/

Each object category contains:

One annotated image: object_000001.jpg

One mask: object_000001_1_gt.png

Multiple unannotated images: object_00000X.jpg

🧠 Approach Overview

Model Used

Segment Anything Model 2 (SAM2) – Tiny variant

Zero-shot inference using bounding box prompts

No fine-tuning or retraining performed