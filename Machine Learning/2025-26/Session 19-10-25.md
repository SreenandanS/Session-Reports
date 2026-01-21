# Session of Machine Learning Division of CyberLabs
Conducted on: 19/10/2025

## Agenda
SimCLR v1, SimCLR v2, Contrastive Learning, Self-Supervised Representation Learning

## Summary
1. The session began with an introduction to self-supervised learning and the motivation behind learning representations without labeled data. We discussed how traditional supervised learning relies heavily on annotated datasets and how contrastive learning provides an effective alternative.
2. SimCLR v1 was introduced, focusing on the core idea of contrastive loss (NT-Xent loss) and how positive and negative pairs are constructed using strong data augmentations. The importance of augmentation strategies such as random cropping, color jitter, Gaussian blur, and normalization was emphasized.
3. We then analyzed the SimCLR architecture, including the encoder backbone and the projection head, and discussed why representations are taken before the projection head during downstream tasks. The role of large batch sizes and temperature scaling in improving contrastive learning performance was also examined.
4. Following this, SimCLR v2 was discussed, highlighting improvements over v1 such as deeper and wider networks, better training strategies, and the introduction of semi-supervised fine-tuning. The concept of freezing the backbone and fine-tuning with limited labeled data was explained in detail.
5. The session concluded with a comparison between SimCLR v1 and v2, focusing on performance gains, training efficiency, and practical use cases in real-world vision tasks.

## Agenda for the next session
* RNN
* LSTM

## Report Compiled by
Rajat Shedshyal 

## Attendees
Third Year Attendees: Mukil M Sir, Harshvardhan Saini Sir, Green Sir 

Second Year Attendees: Anab, Arnav, Ritesh, Rajat, Arjav, Abhishek, Ayushman, Sreenandan, Anukul

## Absentees
Second Year: None
