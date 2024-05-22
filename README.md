These CNN models have been trained to determine the percentage and probability of presence of water in images taken by the satellites, this is achieved by using models like alexnet, resnet, Inceptionv3 and 10 other such models.
The images are splitted into training and test images and masks are split into training masks and testing masks.
The models are trained using the training images and their respective masks, in order to train these models the training images are resized according to the sizes compatible to the respective models,then they are normalized.
After normalizing the images the accuracy and loss of the models are determined then the models are implemented on the test images, that determined their probabliity and presence of water in the images captured by the satellite.
Link for the dataset: https://www.kaggle.com/datasets/franciscoescobar/satellite-images-of-water-bodies
Note: remember to split the images and masks into training and testing images and masks and store them in different files.
