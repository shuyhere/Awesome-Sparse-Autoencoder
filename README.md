# Awesome-Sparse-Autoencoder
Collection of Reverse Engineering in Large Model (and Human Brain...)

## Basis Definitions

**Mechanistic Interpretability** 

[Explainer & Glossary from Neel Nanda](https://dynalist.io/d/n2ZWtnoYHrU1s4vnFSAQ519J)
"MI/mech int/mech interp/mechanistic interpretability: **The field of study of reverse engineering neural networks from the learned weights** down to human-interpretable algorithms. Analogous to reverse engineering a compiled program binary back to source code"

**Features and Circuits**
* [Visualizing Representations: Deep Learning and Human Beings](https://colah.github.io/posts/2015-01-Visualizing-Representations/) (Jan. 16, 2015)
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

**Information, Entropy and KL divergence**

[Elements of Information Theory ](http://staff.ustc.edu.cn/~cgong821/Wiley.Interscience.Elements.of.Information.Theory.Jul.2006.eBook-DDU.pdf)by Thomas M. Cover

## Linear Representation Hypothesis
* [The Linear Representation Hypothesis and the Geometry of Large Language](https://arxiv.org/abs/2406.11944)
* [Not All Language Model Features Are Linear](https://arxiv.org/html/2405.14860v1)

## Superposition

**Superposition**
* [Two kinds of superposition](https://dynalist.io/d/n2ZWtnoYHrU1s4vnFSAQ519J#z=BnAoM1vexv_R8gOkHsPo1LjK)
  * Bottleneck superposition --used for “storage”.
  * Neuron superposition --more features represented in neuron activation space than there are neurons.
* [Softmax Linear Units](https://transformer-circuits.pub/2022/solu/index.html#section-3), "background on how to think about superposition".
  * [Neuroscope: A Website for Mechanistic Interpretability of Language Models](https://neuroscope.io/)
* [Toy Models of Superposition](https://transformer-circuits.pub/2022/toy_model/index.html#computation)
  * related code:
    * [[1.3.1] in Transformer_lens doc : Superposition & Sparse Autoencoders](https://arena3-chapter1-transformer-interp.streamlit.app/%5B1.3.1%5D_Superposition_&_SAEs)

**Polysemanticity, Monosemanticity and Superposition**
* [Towards Monosemanticity: Decomposing Language Models With Dictionary Learning](https://transformer-circuits.pub/2023/monosemantic-features/index.html)

## Sparse Autoencoder
* [Sparse Autoencoders Find Highly Interpretable Model Directions](https://arxiv.org/abs/2309.08600)
* [Towards Monosemanticity: Decomposing Language Models With Dictionary Learning](https://transformer-circuits.pub/2023/monosemantic-features/index.html)
* [Scaling and evaluating sparse autoencoders](https://arxiv.org/abs/2406.04093)

## Transcoders
* [Transcoders Find Interpretable LLM Feature Circuits](https://arxiv.org/abs/2406.11944)
  * code https://github.com/jacobdunefsky/transcoder_circuits
## Sparse Cross-coders

“Crosscoders produce shared features across layers and even models.”

[Sparse Crosscoders for Cross-Layer Features and Model Diffing.](https://transformer-circuits.pub/2024/crosscoders/index.html)

## Train and Evaluate
* [Evaluating Sparse Autoencoders with Board Games](https://adamkarvonen.github.io/machine_learning/2024/06/12/sae-board-game-eval.html)”
* [Scaling and evaluating sparse autoencoders](https://arxiv.org/abs/2406.04093)

## Use Dictionary Learning to Interpret xx of Large Model
