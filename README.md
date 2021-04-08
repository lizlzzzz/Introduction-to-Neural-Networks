# Introduction-to-Neural-Networks
I hope to talk about my own understanding in an easy-to-understand way.

Let's first try to understand neural networks with a simple example.

A man is about to go to the supermarket one day. What factors determine whether he goes to the supermarket or not? For example, Is the weather sunny today? Is it a pleasant day? Is the supermarket open? These three questions can be assumed to be x1, x2, x3, as shown below. These three factors make up the perceptron. If the weather is sunny today, the mood is good and the supermarket is open, then the output y is yes (go to the supermarket); on the contrary, if all three answers are no, then the output y is no (don't go to the supermarket). 

But it may be that each issue affects his visit to the supermarket differently, which leads to a concept called weighting. If the weight for going to the supermarket on a sunny day is 9, the weight for being in a good mood is 5 and the weight for the supermarket being open is 10, and also all three factors are 1 then this leads to a final result of $![CodeCogsEqn](https://user-images.githubusercontent.com/78647916/114064290-63fae900-9891-11eb-8694-8d1bffabc45a.gif). If the good mood factor is 0 and the others are 1, then the final result is ![CodeCogsEqn-3](https://user-images.githubusercontent.com/78647916/114064798-e4214e80-9891-11eb-896d-64308f102d8f.gif). Then there is a threshold for how to decide whether he goes or not. If the threshold is 20, he will go as 24>20 and he will not go as 19<20.

[editing...]

Therefore, from xi (i = 1, 2, 3) to perception and then to the y(result) is a simple process of neural network. 


![gzrsx](https://user-images.githubusercontent.com/78647916/114060964-cd78f880-988d-11eb-9c45-57114f232c8d.png)
