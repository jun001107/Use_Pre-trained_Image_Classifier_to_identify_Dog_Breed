# Use a Pre-trained Image Classifier to identify Dog Breeds
This project was part of the <a href="https://www.udacity.com/course/ai-programming-python-nanodegree--nd089">AI-Programming with Python Nanodegree by Udacity</a>.
<hr>
## Description:
Your city is hosting a citywide dog show and you have volunteered to help the organizing committee with contestant registration. Every participant that registers must submit an image of their dog along with biographical information about their dog. The registration system tags the images based upon the biographical information.

Some people are planning on registerinng pets that <b>aren't actual dogs</b>.

You need to use an already developed <b>Python classifier</b> to make sure the participants are dogs.
<hr>
## My Tasks:
<ul>
  <li>Using your Python skills, you will determine which image classification algorithm works the "best" on classifying images as "dogs" or "not dogs".</li>
  <li>Determine how well the "best" classification algorithm works on correctly identifying a dog's breed.
If you are confused by the term image classifier look at it simply as a tool that has an input and an output. The Input is an image. The output determines what the image depicts. (for example: a dog). Be mindful of the fact that image classifiers do not always categorize the images correctly. (We will get to all those details much later on the program).</li>
  <li>Time how long each algorithm takes to solve the classification problem. With computational tasks, there is often a trade-off between accuracy and runtime. The more accurate an algorithm, the higher the likelihood that it will take more time to run and use more computational resources to run.</li>
</ul>
<hr>
## Important Notes:
For this image classification task you will be using an image classification application using a deep learning model called a convolutional neural network (often abbreviated as CNN). CNNs work particularly well for detecting features in images like colors, textures, and edges; then using these features to identify objects in the images. You'll use a CNN that has already learned the features from a giant dataset of 1.2 million images called ImageNet. There are different types of CNNs that have different structures (architectures) that work better or worse depending on your criteria. With this project you'll explore the three different architectures (AlexNet, VGG, and ResNet) and determine which is best for your application.

We have provided you with a classifier function in classifier.py that will allow you to use these CNNs to classify your images. The test_classifier.py file contains an example program that demonstrates how to use the classifier function. For this project, you will be focusing on using your Python skills to complete these tasks using the classifier function; in the Neural Networks lesson you will be learning more about how these algorithms work.

Remember that certain breeds of dog look very similar. The more images of two similar looking dog breeds that the algorithm has learned from, the more likely the algorithm will be able to distinguish between those two breeds. We have found the following breeds to look very similar: Great Pyrenees and Kuvasz, German Shepherd and Malinois, Beagle and Walker Hound, amongst others.
