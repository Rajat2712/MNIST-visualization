# Data set
The data files train.csv and test.csv contain gray-scale images of hand-drawn digits, from zero through nine.
Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.
The training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.
Each pixel column in the training set has a name like pixelx, where x is an integer between 0 and 783, inclusive. To locate this pixel on the image, suppose that we have decomposed x as x = i * 28 + j, where i and j are integers between 0 and 27, inclusive. Then pixelx is located on row i and column j of a 28 x 28 matrix, (indexing by zero)

![front_page 1](https://user-images.githubusercontent.com/23000971/33508744-6290e3d2-d722-11e7-959c-173ff2f1ae7e.png)


# MNIST Visualization

## Training v/s Validation accuracy plot
![trainacc](https://user-images.githubusercontent.com/23000971/33508768-8fe9e298-d722-11e7-8d62-b07ed2470c4f.JPG)

## Training v/s Validation loss plot
![trainloss](https://user-images.githubusercontent.com/23000971/33508767-8fb6e578-d722-11e7-8172-998ec252fd1a.JPG)

