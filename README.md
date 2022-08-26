# Brain-Tumour-Image-Classification

● Collected image dataset from Kaggle which has the train set and the test set. There are 4 types of brain tumours (Glioma Tumour, Meningioma Tumour, No Tumour, Pituitary Tumour). Image data has also been resized before giving it to the model. Both the training set and testing set got combined. 

● Used transfer learning neural network “EfficientNetB0” to create the neural network with “imagenet” weight. Then added GlobalAveragePooling2D, Dropout and output layers. After compilation with categorical_crossentropy, gave the training set and testing set to the model. After 12 epochs, the model has got the accuracy 96.86% and the validation accuracy 93.88%.
