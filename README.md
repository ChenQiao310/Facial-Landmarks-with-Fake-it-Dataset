# Facial-Landmarks-with-Fake-it-Dataset

Face recognition technology can be widely used in various computer vision tasks such as verifying the identity of a person, swapping faces, and head pose estimation. 

One of the crucial steps of facial recognition tasks is face alignment. This could be effectively done through automated landmark localization. However, as one of the most popular methods to realize facial landmarks localization, deep learning neural networks require a sufficient amount of data for the purpose of training and testing. People often use real world photos to train the model, then test it on the real world data. But collecting data and labeling them for training costs a lot. Can we use the synthetic faces to train the model for the real world faces and get a same or even better result?

In this project, we will use a deep learning neural network model for facial landmarks localization and train it on the CG dataset (as shown in Fig 1), then test it on the real world samples to resolve the domain gap problem between synthetic and real world data.
