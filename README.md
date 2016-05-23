# Meme-Classifier
This is a demonstration of how to build a visual classifier for meme images. The classifier can identify categories (such as "bad luck brian") of meme images by scanning their pixels. As demonstrated in the two itorch notebooks, it can identify 780 meme categories with a confidence greater than 98% (usually). It uses the all-powerful [VGGNet](http://www.robots.ox.ac.uk/~vgg/research/very_deep/) to generate features from pixels and then uses a simple logisitic regression to classify these features. Scroll to the end of the "Train_and_Test" ipython notebook to see an example of the classifier in action. 

# Requirements
* torch
* itorch
* CUDA (Optional)
* cunn (Optional)

