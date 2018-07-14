[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Dog Output"
[image2]: ./images/sample_human_output.png "Sample Human Output"
[image3]: ./images/sample_cnn.png "Sample CNN"

# Project: Convolutional Neural Network Classifier for dog breeds
*Guess a dog's breed based on an image.*
### For Udacity's Machine Learning Engineer and Deep Learning Nanodegrees
<img src="https://github.com/jamesdellinger/machine_learning_deep_learning_nanodegree_dog_project/blob/master/mlndlogo.png" height="140">     <img src="https://github.com/jamesdellinger/machine_learning_deep_learning_nanodegree_dog_project/blob/master/dlndlogo.png" height="140">

### Topic: Deep Learning

### Overview:

* I built a pipeline that can be used within a web or mobile app to process real-world, user-supplied images.
* I explored several state-of-the-art CNN models for image classification, ultimately using transfer learning to build my own classifier for dog images on top of a pre-trained [Inception v3](https://arxiv.org/abs/1512.00567) bottleneck.
* Given an image of a dog, my algorithm identifies an estimate of its breed:

    <img src="https://github.com/jamesdellinger/machine_learning_deep_learning_nanodegree_dog_project/blob/master/images/sample_dog_output.png" height="170">
* If supplied an image of a human, my code infers the most nearly resembling dog breed:

    <img src="https://github.com/jamesdellinger/machine_learning_deep_learning_nanodegree_dog_project/blob/master/images/sample_human_output.png" height="170">

### Concepts:

*

### My completed project is here:

* [ipython notebook](https://github.com/jamesdellinger/machine_learning_nanodegree_dog_project/blob/master/dog_app.ipynb) / [html version](http://htmlpreview.github.com/?https://github.com/jamesdellinger/machine_learning_nanodegree_dog_project/blob/master/report.html) / [pdf version](https://github.com/jamesdellinger/machine_learning_nanodegree_dog_project/blob/master/dog_app.pdf)

### Project Grading and Evaluation:

* [Project Review](https://github.com/jamesdellinger/machine_learning_nanodegree_dog_project/blob/master/dog_project_review.pdf)

* [Project Grading Rubric](https://github.com/jamesdellinger/machine_learning_nanodegree_dog_project/blob/master/dog_project_grading_rubric.pdf)




Along with exploring state-of-the-art CNN models for classification, you will make important design decisions about the user experience for your app.  Our goal is that by completing this lab, you understand the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline.  Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer.  Your imperfect solution will nonetheless create a fun user experience!
