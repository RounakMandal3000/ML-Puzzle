# ML-Puzzle
In this problem the task was to classify each point in each image present inside the TestSet file using the images present inside Type 1 and Type 2 files. 
I found the coordinates of the particles in each image using numpy and then used it to create an array on which I used an Artificial Neural Network to train. Then using
cv2.rectangle function I drew green rectangles around the type 1 particles and red around type 2. The Output_Images.zip contains the output images with rectangles 
classifying each particle. I got an accuracy of 70% with a F1 score of 0.53 on the cross validation data. The Model.ipynb is the code of the model I implemented in 
Google Colab.
