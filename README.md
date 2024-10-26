# Awesome-Sparse-Autoencoder
Collection of Reverse Engineering in Large Model (and Human Brain...)

## Basis Definitions

**Mechanistic Interpretability** 

[Explainer & Glossary from Neel Nanda](https://dynalist.io/d/n2ZWtnoYHrU1s4vnFSAQ519J)
"MI/mech int/mech interp/mechanistic interpretability: **The field of study of reverse engineering neural networks from the learned weights** down to human-interpretable algorithms. Analogous to reverse engineering a compiled program binary back to source code"

**Features and Circuits**
* [Feature visualization](https://distill.pub/2017/feature-visualization/) (Nov. 7, 2017)
  "**Feature visualization** answers questions about what a network or parts of a network are looking for by generating examples.

  Neural networks are, generally speaking, differentiable with respect to their inputs. If we want to find out what kind of input would cause a certain behavior,whether that’s an internal neuron firing or the final output behavior,we can use derivatives to iteratively tweak the input towards that goal."
* [Zoom In: An Introduction to Circuits](https://distill.pub/2020/circuits/zoom-in/) (March 10, 2020)
  "By studying the **connections between neurons**, we can find meaningful algorithms in the weights of neural networks."

**Open Problems in Mechanistic Interpretability**

* [200 Concrete Open Problems in Mechanistic Interpretability: Introduction](https://www.lesswrong.com/posts/LbrPTJ4fmABEdEnLf/200-concrete-open-problems-in-mechanistic-interpretability)
  * The Case for Analysing Toy Language Models
  * Looking for Circuits in the Wild
  * Interpreting Algorithmic Problems
  * Exploring Polysemanticity and Superposition
  * Analysing Training Dynamics
  * Techniques, Tooling and Automation
  * Image Model Interpretability
  * Reinforcement Learning
  * Studying Learned Features in Language Models

**Hebbian theory**

_"Neurons that fire together wire together."_(connect to the activations in neural network, [3B1B post](https://www.3blue1brown.com/lessons/backpropagation))
[Hebbian theory](https://en.wikipedia.org/wiki/Hebbian_theory#:~:text=Hebbian%20theory%20is%20a%20neuropsychological,neurons%20during%20the%20learning%20process) is a neuropsychological theory claiming that an increase in synaptic efficacy arises from a presynaptic cell's repeated and persistent stimulation of a postsynaptic cell. It is an attempt to explain synaptic plasticity, the adaptation of brain neurons during the learning process. It was introduced by Donald Hebb in his 1949 book The Organization of Behavior.


## Superposition

## Sparse Autoencoder

## Transcoders

## Sparse Cross-coders

## Train and Evaluate

## Use Dictionary Learning to Interpret Large Model
