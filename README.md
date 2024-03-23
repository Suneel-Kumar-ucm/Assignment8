# Assignment8


Name: Suneel kumar reddy katikareddy NetworkId:sxk66390

VIDEO-LINK: https://drive.google.com/file/d/1SebSri9xrXZZpIIxRz8h0cip6HirqvC2/view?usp=drive_link

1.Add one more hidden layer to autoencoder In this code first we have executed the code which was given then we have added some hidden layers in encode(the encoded representation of the input) and in decode(the lossy reconstruction of the input) and this model plots an input to its reconstruction and also the encoder for its encoded representation and then compiling the model and loading the MNIST dataset after that normalize and flatten the data then train the autoencoder.

<img width="589" alt="image" src="https://github.com/Suneel-Kumar-ucm/Assignment8/assets/156639138/edcf3b69-94c5-45a7-9f8e-b0eb48c315a4">



2.Do the prediction on the test data and then visualize one of the reconstructed version of that test data. Also, visualize the same test data before reconstruction using Matplotlib
for this we are using the matplotlib lib and then getting the reconstructed images for the test set. And choose a random image from the test set based on the index of the image to be plotted then plotting the orginal image as well as plotting the reconstructed image by using an imshow() function.

<img width="465" alt="image" src="https://github.com/Suneel-Kumar-ucm/Assignment8/assets/156639138/3f0ea146-8041-4d96-9b7f-65cc619a2123">


3. Repeat the question 2 on the denoisening autoencoder Here we are repeating the step 2 which we have done for autoencoder,in this first we have executed the code which is given and then added few lines like plotting the orginal noisy and reconstructed image by getting the recostructed images for the test set and then choosing a random image from the test set.

<img width="476" alt="image" src="https://github.com/Suneel-Kumar-ucm/Assignment8/assets/156639138/2603ae45-d237-4d0d-81aa-d1eb7881feb8">


4.plot loss and accuracy using the history object. Importing the matplotlib, here we are training the autoencoder by using the autoencoder.fit() function and then plotting the both loss and accuracy by using the plot() function by declaring the title, xlabel, ylabel functions we are displaying the graphs of both loss and accuracy.


<img width="608" alt="image" src="https://github.com/Suneel-Kumar-ucm/Assignment8/assets/156639138/84a57714-383c-4b87-a473-ba6f3d327365">

<img width="579" alt="image" src="https://github.com/Suneel-Kumar-ucm/Assignment8/assets/156639138/4bed9f14-f17d-48ae-83c2-b38d9f03b65e">


<img width="412" alt="image" src="https://github.com/Suneel-Kumar-ucm/Assignment8/assets/156639138/2bc3681d-a8c2-4ca2-87a9-50a5a678016e">


