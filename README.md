# RNN-lifearchitecture-
A foray into Recurrent networks as an architecture for life 

---

## Architecture of a canonical RNN

** ADD IMAGE OF ARCHITECTURE **

An RNN operates on the basis of LSTMs and a very important aspect -  it's hidden state vector *h*.
From the perspective of human cognition, we can see why such a caveat is quite important. 
Following reading's from Karpathy's blog post:

> The RNN class has some internal state that it gets to update at every time **step**. In the simplest case, this state consists of a single *hidden* vector **h**.

One could see how such a hidden vector state **h** could be analogized to a sort of subconsious thought process - similar to that found in humans.

### How could we define conscious thought? (Proper explanation of connection)
Conscious subjective experience, or *qualia* as some like to call it might not be as complex as some would like to imagine it is. Of course I don't claim to have all the answers, far from it actually. I do feel though that I might be looking in the right direction.

When a thought comes to mind, a smell is sensed, or luminous intensity from a light source is perceived, there is quite alot of background computation going on. 

Let's make some preliminary mappings:
Following the principle of a simple mlp, we have an output **y = (W.x) + b** . This is the basis of a computational neuron.

#### Input (x)
We could analogize the input **x** as a high dimensional vector of datapoints mapping to senses (sight, smell, sounds etc). These input points can be efficently compressed by some compression/tokenization algorithm into sequential inputs.


