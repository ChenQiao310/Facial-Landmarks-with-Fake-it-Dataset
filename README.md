# Facial-Landmarks-with-Fake-it-Dataset

Face recognition technology can be widely used in various computer vision tasks such as verifying the identity of a person, swapping faces, and head pose estimation. 

One of the crucial steps of facial recognition tasks is face alignment. This could be effectively done through automated landmark localization. However, as one of the most popular methods to realize facial landmarks localization, deep learning neural networks require a sufficient amount of data for the purpose of training and testing. People often use real world photos to train the model, then test it on the real world data. But collecting data and labeling them for training costs a lot. Can we use the synthetic faces to train the model for the real world faces and get a same or even better result?

In this project, we used deep learning neural network models such as Xception and ResNet50 for facial landmarks localization and trained it on the CG dataset, then tested it on the real world samples to resolve the domain gap problem between synthetic and real world data.

Dataset:

The training set will be drawn from the Microsoft CG dataset (https://github.com/microsoft/FaceSynthetics) containing 100,000 images of synthetic faces at 512*512 pixel resolution (shown in Fig 2). The labels of the training set are 2D landmark coordinates which are also provided alongside the images.

The images of the testing set will be chosen from Flickr-Faces-HQ (FFHQ) (https://github.com/NVlabs/ffhq-dataset).  FFHQ was originally built as a benchmark  for generative adversarial networks (GAN). It contains 70,000 high-quality images of human faces at 1024×1024 resolution. 
