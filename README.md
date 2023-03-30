# 700745488--Assignment-8-Ashwin-kumar-Reddy

Here is the video which states the description about the code
https://drive.google.com/file/d/1l0A0RpFgF-KBhVel7_NeA8kp9E_Wirk-/view?usp=sharing

1. Tune hyperparameter and make necessary addition to the baseline model to improve validation accuracy
and reduce validation loss.
2. Provide logical description of which steps lead to improved response and what was its impact on
architecture behavior.
3. Create at least two more visualizations using matplotlib (Other than provided in the source file)
4. Use dataset of your own choice and implement baseline models provided.
5. Apply modified architecture to your own selected dataset and train it.
6. Evaluate your model on testing set.
7. Save the improved model and use it for prediction on testing data
8. Provide plot of confusion matric
9. Provide Training and testing Loss and accuracy plots in one plot using subplot command and history object.
10. Provide at least two more visualizations reflecting your solution.
11. Provide logical description of which steps lead to improved response for new dataset when compared with
baseline model and enhance architecture and what was its impact on architecture behavior.

A) Here in this program we use numpy beacause it is used to perform a wide variety of mathematical operations on arrays, and also matpotlib is used here for creating 2D-Graphs and also seaborn is used to understand and explore your data, and tensorFlow gives you the flexibility and control with features like the Keras Functional API and Model Subclassing API for creation of complex topologies and from tensor kensor datasets we are importing, we also use  MNist to test and compare research results with others. RMS prop is used to accelerate the optimization process and dense layer is used to classify image based on output from convolutional layers and flatten is used to convert all the resultant 2-Dimensional arrays from pooled feature maps into a single long continuous linear vector, and  Conv2D is imported because it is a 2D Convolution Layer, this layer creates a convolution kernel that is wind with layers input which helps produce a tensor of outputs. Here Max pooling is a type of operation that is typically added to CNNs following individual convolutional layers. From here we are extracting dataset and train it and then testing it and then finding the accuracy by predicting it then subsequently find the plot of confusion matric, further providing trainig and testing loss and accuracy plots in one plot using subplot command and history object and then providing at least two more visualizations reflecting solution and lastly providing logical description of steps which lead to improved response for new dataset when compared with baseline model and then enhancing architecture based on the final accuracy
