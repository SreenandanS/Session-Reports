# Session of Machine Learning Division of CyberLabs
Conducted on: 17/08/2025

## Agenda
MobileNetV2, U-Net, and EfficientNet

## Summary
1. Analyzed the shift from standard residuals to Inverted Residuals in MobileNetV2 and why connecting thin bottleneck layers is more memory-efficient.
2. Discussed the intuition behind Linear Bottlenecks, specifically how non-linear activations like ReLU can destroy information in low-dimensional spaces.
3. Compared the concatenation method in U-Net skip connections to the summation used in ResNet, noting how it preserves spatial texture for precise localization.
4. Examined the Symmetric path of U-Net and how the decoder effectively reconstructs the image from the low-resolution context provided by the encoder.
5. Critiqued traditional manual scaling methods (just adding layers vs. just adding channels) and why they eventually lead to accuracy saturation.
6. Evaluated the Compound Scaling rule in EfficientNet as a method to balance depth, width, and resolution simultaneously for better FLOPs efficiency.
7. Explored the role of Neural Architecture Search (NAS) in creating the EfficientNet-B0 baseline and how it optimizes for both accuracy and latency.
8. Briefly touched upon the integration of Squeeze-and-Excitation blocks within the MBConv layers to help the model focus on the most important feature channels.


## Agenda for the next session
* RCNN

## Report Compiled by
Anab Farooq

## Attendees
Fourth Year Attendees: Karaka Prasanth Naidu Sir, Manav Jain Sir. 

Third Year Attendees: Green Kedia Sir, Mukil M Sir, Harshvardhan Saini Sir, Daksh Mor Sir, Mohd. Ashaz Khan Sir, Priyam Pritam Panda Sir, Abhinav Jha Sir, Dilshad Sir

Second Year Attendees: Anab, Arnav, Ritesh, Rajat, Arjav, Abhishek, Ayushman, Sreenandan, Anukul

## Absentees
Second Year: None
