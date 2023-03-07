Problem Statement

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


Dataset

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images.




Conclusion

1. Analysis of CNN architecture without augmentation:
Training accuracy - 88%
Validation accuracy - 55.48%

Inference - Overfitting

2. Analysis of CNN architecture (with augumentation technique):
Training accuracy - 43.81%
Validation accuracy - 43.40

There is significant reduction in accuracy.

3. Analysis of CNN architecture (After treating class imbalance):
Training accuracy - 96.36%
Validation accuracy - 83.74%

There is significant increase in accuracy of both training and validation sets. Also there is good reduction in both training and validation loss.





