EX3 Object Detection

In https://towardsdatascience.com/creating-your-own-object-detector-ad69dda69c85
there is an explanation how to run an object detection algorithm. It is somewhat technical (no real programming) but doable.
Basically you take a trained model (there are lots of them in the model zoo) and train it to the classes you want. You can then test the algorithm on some test images. The algorithm detects the objects in the images returning a set of bounding boxes their classes and the probability that the object belongs to the class.
So choose a few (2-3) classes you want to detect. Take a few dozen images in which the objects appear. Divide them into train and test. Label the images using labelimg and then train the model for your classes. Once the algorithm has converged generate a program to run the algorithm on the test images.
Maybe think about a post processing step you want to run on the output to yield a higher level of understanding.
At the end write a report on your project and show in it some results (good and bad).
I will open a forum for you to ask and answer questions about the technical problems you might run into.
Good Luck.
