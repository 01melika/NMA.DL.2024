Can a computer see similarity like a human?

This project is about training a computer program to find the odd image out of three, just like you can!  We're using a special kind of program called a Siamese neural network.

Here's the idea: Imagine you see three pictures: a cat, a dog, and another cat. You can easily tell the dog is different because of its shape and fur. The Siamese network will learn to do this too, by looking at many triplets of images. 

The researchers want to see if this network can perform as well as humans, even when the images are slightly different (like having noise or the object being turned at an angle). 

This project uses special tools (like  PyTorch) to train the network and test its abilities. The researchers will then see if the network can be a helpful tool for tasks like image search or organization. 

The inspiration for this project comes from a [NIH paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7666026/#R17) that demonstrates how human object similarity can be recreated through an embedding matrix and a modeling algorithm. Our implementation strives to achieve the same objective but leverages a neural network instead.

**The code is like a recipe for teaching a computer to see like a human.** 

It starts by gathering a bunch of pictures grouped in threes. Two pictures in each group are similar (like two cats), and one is different (like a dog). The code then teaches the computer to recognize these differences by showing it many, many groups of pictures.

Once the computer has learned, the code tests it by giving it new groups of pictures and seeing if it can correctly pick out the odd one. 

Think of it as teaching a child to tell the difference between apples and oranges by showing them lots of examples. 



