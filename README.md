# *M.I.A.*
<p align="center">
Quantifies the mutual information in an autoencoder mimicking an end-to-end communication system. 
</p>  

## Mutual Information Overview
The mutual information, denoted by **I(X;Y)**, is an information theoretic concept that quantifies the level of depandency between two random variables, **X** and **Y**, with entropies **H(X)** and **H(Y)**, respectively.

![mi](https://user-images.githubusercontent.com/44330120/47536122-45474880-d90a-11e8-8d8b-0f24e2509c38.png)

Since even intuitively information is always "in something about something else", the mutual information actualy captures the amount of information in **X** about **Y**.

## Mutual Information Revisited
In an effort to better understand source message representation in autoencoders, this project quentifies the mutual information between the source message and the hidden layers, and the mutual information between the hidden layers and the decoded message at the destination.

## Prerequisites 
The code requires:

* TensorFlow

`$ pip install TensorFlow`

* Numpy

`$ pip install numpy`

* Matplotlib

`$ pip install -U matplotlib`

## Further reading
Check out my other repo CommsCoder for the rational behind using autoencoders as communication systems. In https://arxiv.org/pdf/1703.00810.pdf you can find details on information theory in deep learning. See http://math.harvard.edu/~ctm/home/text/others/shannon/entropy/entropy.pdf for further info on communication systems, and http://ufldl.stanford.edu/tutorial/unsupervised/Autoencoders/ for a very good and concise explination on autoencoders. 
