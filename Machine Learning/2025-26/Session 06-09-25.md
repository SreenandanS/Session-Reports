# Session of Machine Learning Division of CyberLabs
Conducted on: 06/09/2025

## Agenda
Object Detection Fundamentals, R-CNN, and Fast R-CNN

## Summary
1. ⁠Evolution of Object Detection: Transition from sliding window approaches to region proposal methods to manage computational complexity
2. Selective Search Algorithm: Discussion on using hierarchical grouping of similar pixels based on color, texture, size, and shape to generate ~2000 candidate regions.
3. ⁠R-CNN Architecture: Detailed walkthrough of the three-stage pipeline: Region Proposal, Feature Extraction (via CNN), and Classification/Bounding Box Regression.
4. Warping and Pre-processing: The necessity of resizing region proposals to a fixed 224 x 224 input size for the CNN, and the impact of aspect ratio distortion.
5. Feature Extraction: Leveraging pre-trained ImageNet models (like AlexNet) and fine-tuning them for the specific detection task.
6. Classification vs. Detection: Why SVMs (Support Vector Machines) were used for final classification instead of a Softmax layer in the original R-CNN paper.
7. ⁠Bounding Box Regression: Mathematical intuition behind refining the coordinates of the predicted box to better fit the ground truth.
8. ⁠Bottlenecks of R-CNN: Analysis of why the original model is slow (offline feature storage) and expensive in terms of disk space and inference time.
9. ⁠Introduction to Fast R-CNN: Solving the speed bottleneck by passing the entire image through the CNN once rather than processing 2000 individual crops.
10. ⁠RoI (Region of Interest) Pooling: How to extract fixed-length feature vectors from valid regions of a feature map to enable end-to-end training.

## Agenda for the next session
* Faster RCNN

## Report Compiled by
Anukul Tiwari

## Attendees
Third Year Attendees: Mukil M Sir, Harshvardhan Saini Sir

Second Year Attendees: Anab, Arnav, Ritesh, Rajat, Arjav, Abhishek, Ayushman, Sreenandan, Anukul

## Absentees
Second Year: None
