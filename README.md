# Assignment8


Name: Suneel kumar reddy katikareddy NetworkId:sxk66390

VIDEO-LINK: 

Add one more hidden layer to autoencoder In this code first we have executed the code which was given then we have added some hidden layers in encode(the encoded representation of the input) and in decode(the lossy reconstruction of the input) and this model plots an input to its reconstruction and also the encoder for its encoded representation and then compiling the model and loading the MNIST dataset after that normalize and flatten the data then train the autoencoder.


Do the prediction on the test data and then visualize one of the reconstructed version of that test data. Also, visualize the same test data before reconstruction using Matplotlib
for this we are using the matplotlib lib and then getting the reconstructed images for the test set. And choose a random image from the test set based on the index of the image to be plotted then plotting the orginal image as well as plotting the reconstructed image by using an imshow() function. 

Repeat the question 2 on the denoisening autoencoder Here we are repeating the step 2 which we have done for autoencoder,in this first we have executed the code which is given and then added few lines like plotting the orginal noisy and reconstructed image by getting the recostructed images for the test set and then choosing a random image from the test set.


plot loss and accuracy using the history object. Importing the matplotlib, here we are training the autoencoder by using the autoencoder.fit() function and then plotting the both loss and accuracy by using the plot() function by declaring the title, xlabel, ylabel functions we are displaying the graphs of both loss and accuracy.
