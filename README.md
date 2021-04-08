# Introduction-to-Neural-Networks
I hope to talk about my own understanding in an easy-to-understand way.

Let's first try to understand neural networks with a simple example.

A man is about to go to the supermarket one day. What factors determine whether he goes to the supermarket or not? For example, Is the weather sunny today? Is it a pleasant day? Is the supermarket open? These three questions can be assumed to be x1, x2, x3, as shown below. These three factors make up the perceptron. If the weather is sunny today, the mood is good and the supermarket is open, then the output y is yes (go to the supermarket); on the contrary, if all three answers are no, then the output y is no (don't go to the supermarket). 

But it may be that each issue affects his visit to the supermarket differently, which leads to a concept called weighting. If the weight for going to the supermarket on a sunny day is 9, the weight for being in a good mood is 5 and the weight for the supermarket being open is 10, then this leads to a final result of 9*1 + 5*1 + 10*1 = 24






Therefore, from xi (i = 1, 2, 3) to perception and then to the y(result) is a simple process of neural network. 




Weighting: The weighting is the extent to which these three questions influence whether the person goes to the supermarket or not. For example, if it is a sunny day, the weight of the person going to the market is 0.9, 0.5 for a cloudy day and 0.2 for a rainy day.


![gzrsx](https://user-images.githubusercontent.com/78647916/114060964-cd78f880-988d-11eb-9c45-57114f232c8d.png)
