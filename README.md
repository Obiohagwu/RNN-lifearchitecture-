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

- **Input (x)**: We could analogize the input **x** as a high dimensional vector of datapoints mapping to senses (sight, smell, sounds etc). These input points can be efficently compressed by some compression/tokenization algorithm into sequential inputs.
- **Weights (W)**: The weights are the really important part. For those unfamiliar, you could imagine a weight matrix as the  directional arm of the scalar, granting it magnitude and direction - ergo a vector. Think speed vs velocity, or mass vs gravity. **A weight matrix is a directed sequence**. Weights are important in so far as they hold, through iterative optimization via backpropagation, the optimal datapoints that leads our model to produce ideal outputs. In this analogy of RNNs as life architectures, a weight can be mapped to **conscious attention**. Consciousness, without the directional value of attention, or an attention mechanism, is almost quite useless. The reasons for that are fairly obvious once you think about it. Consciousness for all it's worth, is simply directed attention.
- **bias (b)**: The bias term is important insofar as most of our subjective experince is clouded by a fugue of internal mechanics that we can't accurately account for. Bias is also useful for avoiding problems of overfitting to a certain mode of operation (overfitting/underfitting), allowing our model to generalize better over multiple schemas.


## The step function and it's significance to hidden state approximation
