# Skin-Cancer-Detection
Detecting skin cancer and Classifying as either Melanoma, Nevus or Seborrheic Keratosis

In this Notebook I tried to approach this problem using different techniques.
1.Transfer Learning using the Inception model trained on the ImageNet dataset.
2.Transfer Learning using the Xception model trained on the ImageNet dataset.
3.Fine-tuning the last two blocks of the Inception model.

Although I applied Fine Tuning to the Inception model but It did not yield any good results 
maybe because of very small Dataset. Moreover, training images were more biased towards the 
Nevus class. We had about 3 times less Images of Melanoma in the Training dataset but the 
Testing dataset had equal percentages of all the classes. That is why training loss was way smaller
than the testing loss.

