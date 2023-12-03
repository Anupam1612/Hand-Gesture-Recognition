# Hand-Gesture-Recognition
Solution for physically challenged people.


This project is totally divided into four parts, as follows:

1. Capture live images for all the hand gesture classes.
2. Create a dataset using an open-source framework called'mediapipe' created by Google.
3. Train our Random Forest classifier and save our model parameters.
4. Inference from that classifier.


--> collection_of_images.py file opens a webcam of our system and captures 100 images of each class using open-CV.
--> Create_Dataset.py file Create a dataset from the above captured images using 'mediapipe' framework.
--> Classifier_Traning.py file trains the classifier using an already-created dataset and saves the model as a model.p file.
--> main.py use model.p file to infer that trained classifier to classify live hand gestures and indicate what is detected using playsound liberary.


# Conclusion

The main objective of this project is to create a model that can help physically challenged people communicate easily with others.
