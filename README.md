# FACE-DETECTION-AND-RECOGNITION-SUBHROJYOTI
Performs face detection and recognition using VGGnet
Cell 1- imports necessary libraries performs necessary pre-transformations on the image and returns the bounding box tensors.
Cell 2 - Mounting the Google Drive.
Cell 3 -This code defines a custom collate function named collate_fn for a PyTorch DataLoader, which takes a batch of samples, where each sample is a tuple containing an image, a list of bounding boxes, and a list of corresponding object names, and organizes them into batches with stacked images, a list of all bounding boxes, and a list of all object names.
Cell 4- loading the annotations JSON file.
Cell 5 -Partition into train and test and validation datasets.
Cell 6 - normalize the required image and use a pre-trained VGGnet classifier and define the criteria of MSE loss.
Cell 7  and 8 take the first batch of images required followed by inverse normalization.
Cell 9 -define the vggnet model.
Cell 10-set the required parameters including the number of layers, activation functions, etc.
Cell 11-training the VGGnet model on the custom dataset for 50 epochs
Cell 12 -plot of error
Cell 13 -evaluation of reqd model.
Cell 14 - first batch after training the model on custom dataset.
Cell 15-inverse normalization with required results.
Normalization- Normalization in image processing refers to the process of standardizing the pixel values of an image to a common scale, typically with a mean of 0 and a standard deviation of 1. 
Inverse Normalization - Inverse normalization in image processing is the process of reverting normalized pixel values back to their original scale after a normalization transformation has been applied. 
Link to the dataset -https://drive.google.com/drive/folders/1cxuEV5SEOLM7t6NLtNpV8wVOTdlcmfUe?usp=drive_link







