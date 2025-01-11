DAY 1 
we used CNN model and preprocessed 30% of data for training and tested a single image for prediction
![Screenshot 2025-01-07 210945](https://github.com/user-attachments/assets/dc367d61-3efa-48ae-adbf-8c5ddb2e0575)

DAY 2 

we added more data upto 90 % of data for preprocessing and evaluated by (80/20) approach with 50 epochs 
later it gives 40 % accuracy

![image](https://github.com/user-attachments/assets/27086c2b-f963-4f71-8d6e-fc590775433b)

DAY 3

We used MobileNetV2 CNN model with 80% data for training and 20% for testing.
10 images of each class were randomly selected and allowed for testing. 94 out of 100 predictions were correct.

![Screenshot 2025-01-07 204533](https://github.com/user-attachments/assets/70196c2f-933d-445d-8de0-989aa6e15ee5)

DAY 4

The MobileNetV2 model is trained with 100 epochs which leads to 94-97% accuracy in randomly selected preprocessed data and 81-90% accuracy in randomly selected raw data.
The model is tested with extra images, 3 out of 26 images were identified correctly.

![image](https://github.com/user-attachments/assets/2b94d19c-f644-4c3e-a09e-c2cda894e59e)

DAY 5 

We tried to increase the accuracy of MobileNetV2 model with more epochs(increased from 100 to 200) and different batch sizes, but it could not improve its efficiency on new images

DAY 6

We trained two models namely efficientnet and resnet101. Efficientnet gave only 12.50% accuracy for images in the dataset and identified 3 out 26 external images. But resnet101 identified 7 out of 26 images in the external images, eventhough having 36% accuracy in the trained dataset.

DAY 7


We tried to improve the accuracy of the resnet101 model with more epochs(250). There was improvement in accuracy for identifying images on the trained dataset, but there was no improvement in the accuracy for unseen dataset.
