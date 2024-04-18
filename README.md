# Face-Mask-Detection

The Dataset contains images of people wearing masks and people not wearing masks. The database contains 10,000 colored images in the training folder, 800 images in the validation folder, and 992 images in the test folder.

The task is to create a CNN model for identifying whether a person in the image is wearing a mask or not.

The following tasks are performed:

Create test, train, and validation directory variables <br>
Create train and validation data generator with target size (128,128) <br>
Train a CNN model <br>
Train a model with VGG19 model <br>
Use callbacks to save your model at every step <br>
Use 5 to 10 epochs only <br>
