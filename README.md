# Challenge-4-Object-Distance
This project was a continuation off of challenge 3. In this challenge, the goal was to predict the distance of a traffic cone in a given image.

Initially, I tried to use a Keras model with 3 convolutional layers and 2 dense layers using a relu activation function and the adam optimizer. After running this model, I realized that the model wasn't learning as it was simply outputting zero values as predictions. After making some adjustments to the Keras model, I decided to use a regression decision tree. To test it's ability, I adjusted the image sizes from (1920, 1080) to (240, 135) and appended them to an array and then flattened the array. This approach worked and lead to using the regression decision tree with image sizes of (960,540).
