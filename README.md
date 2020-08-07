# Chest_X-Ray_Project
##Binary Classifiacation
![Binary] (Binary.png)
**This project diagnoses pneumonia from Chest X-Ray images using convolutional neural network and tranfer learning via inception-V3. The images were of size greater than 1000 pixels per dimension and the total dataset was tagged large and had a space of 1.2 Gb . Our work includes neural network architecture for Binary followed by Categorical ('Normal','Viral Pneumonia','Bacterial Pneumonia') Classification which was fine tuned for efficient hyperparameters and used variety of utility function of keras like callbacks for learning rate reduction and checkpointing. Using ImageDataGenerator from tensorflow we augmented the training image data to prevent overfitting along with the conventional regularisation methods such as Dropout, L1 and L2 Regularzations and Earlystopping. Other evaluatory metrics like Precision , Recall and F1 score were monitored using confusion matrix. The accuracy on test data was 91.51% and the F1 score was 0.937.
We also classified the X-Ray images into  ('Normal','Viral Pneumonia','Bacterial Pneumonia') classes using the same model but because of insufficient data for each class the accuracy reached only 83.81%** 
##Multiclass Classification
![categorical] (categorical.png)
