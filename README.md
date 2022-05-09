# image_colorization

The code for my project is a python notebook named "colorization.ipynb". I ran it using google drive.

The first three cells sets up the environment with imports and path definitions. Then, the class DataLoader initializes the input data by resizing and pre-processing the images into training and validation splits. Then, the model is defined in get_model(), and training parameters are initialized below that. A batch generator is used, and the weights are saved per epoch. The last cell uses the model to make predictions on the validation images and saves them.
