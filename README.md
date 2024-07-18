![Screenshot (1761)](https://github.com/user-attachments/assets/517ee22f-a1a5-46d1-aa1d-c4b0299e1d5c)

This is a deep learning project that predicts whether a potato plant is healthy  or has got disease like early blight or late blight  ,  based on  image of the plant leave provided.

- Image Dataset is taken from kaggle and various operations like data augmentation, scaling are done on dataset images for generating more
   images and preventing overfitting conditions with the help of tensorflow dataset pipeline usage.
   
- Then convolutional neural network is used for model training and trained model is saved.

- backend server is built using fastapi for serving prediction request.

- frontend is built using react js for uploading leaf image.



