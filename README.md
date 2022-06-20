# Intel-Image-Classification-Project
I created image data directory having separate folders for each image class.

I did Data augmentation by using keras ImageDataGenerator.flow_from_directory class object.

Initially used a CNN model as a base model to extract features from the image

Then applied transfer learning by importing weights(Fully connected dense layers) from keras.applications.vgg16

created a small new test dataset for the prediction using previously trained model.
