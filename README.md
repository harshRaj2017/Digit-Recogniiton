# Digit-Recogniiton
This Python project Recognizes Handwritten digits using Artificial Neural Network

Requirements : Python 3.5,sklearn,opencv,numpy,imutils
> train.py file is used for training the model

> test.py file is used for Testing the model on test dataset,It picks up the model from model.pkl file

> model.pkl file is our trained Neural Network

> test_on_image.py file is used to test our ANN model on actual images

> sample_images represent the images on which the model is tested

> One of the Sample Image is as follows:

![alt text](https://ibb.co/n0P4Spy)

> Recognized digits are as Follows:

![alt text](https://ibb.co/xC1b3hY)

>Another sample image is ,

![alt text](https://ibb.co/NSTcWX1)

>Its result is:

![alt text](https://ibb.co/RH3nR8c)


> As we can see in above image ,one of our digit gets classified incorrectly!

> One of the key thing to remember here is that extracting digit area from the natural image requires thresholding
	which is ofcourse in some cases leads to error,hence testing images should have proper exposure and evenly 
	distributed brightness