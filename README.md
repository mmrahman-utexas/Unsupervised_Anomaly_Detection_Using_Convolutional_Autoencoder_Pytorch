# Unsupervised_Anomaly_Detection_Using_Convolutional_Autoencoder_Pytorch
Built an unsupervised dataset from a supervised labeled dataset of MNISt dataset by removing its labels. Then defined a Convolutional
Autoencoder network in PyTorch and trained it on the unsupervised dataset and allowed the network to learn to reconstruct the training
images containing regular image with a small percentage of anomaly images. Then during inference, I set a reconstruction error (MSE)
threshold based on a given percent quantile and declared a input image as a anomaly for who's the image reconstruction error is above the
preset threshold.
