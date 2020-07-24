## Hand Written Digit Recognition using -
#### -KNN
#### -MNIST Dataset
## Using KNN
KNN is a simple machine learning classifier that classifiers a new
input based on the closest examples in the feature space.
It’s based on the weighted Euclidean distance of the k-nearest
neighbors.
### About the Digits Dataset-
- The digits.png image contains 500 samples of each numeral (0-9).Total of 5000 samples of data.
- Each individual character has dimensions: 20 x 20 pixels Is grayscale with black backgrounds.
- 500 samples of each digit with 5 rows of 100 samples
- Each character is a grayscale 20 x 20 pixels
- Numpy to arrange the data in this format: 50 x 100 x 20 x 20
- Then split the training dataset into 2 segments and flatten our 20x20array.
- Training Set - 70% of the data
- Test Set - 30% of the data - we use a test set to evaluate our model
- Each dataset is then flattened, meaning we turn the 20 x 20 pixel array into a flat 1 x 400. Each row of 20 pixels is simply appended into one long column.
- Assign labels to both training & test datasets (i.e. 0,1,2,3,4,5,6,7,9)

## Using MNIST
- It is a fairly large dataset consisting of 60,000 training images and 10,000 test images.
### About the Procedure-
- Loading the Data into Keras
- Getting our data in Shape using Numpy and Transformations on Training and Test Image Data
- Building & Compiling Our Model
- Training the model and using it to on test images.
