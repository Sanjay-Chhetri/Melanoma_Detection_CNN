# Melanoma_Detection_CNN
Melanoma Detection using CNN 
## Problem Statement
  To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:-
Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

## Final Analaysis
As per the above data:
Training Accuracy = 0.9137
Validation Accuracy = 0.8643
Training Loss = 0.2305
Validation Loss = 0.3523

1. The Validation Accuracy is now improved to 0.8643 and Training Accuracy to 0.9137</br>
2. There is a significant reduction in loss of both training and Validation sets.</br>
3. The model is not overfit. Class rebalance using Augmentor has helped to solve the issue of Overfitting.</br>
