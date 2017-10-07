# AI and DeepRL

This repository provides source code, links and other learning materials related to Artificial Intelligence, especially focused on Deep Reinforcement Learning.

## Texts

Sutton and Barto provided the definitive textbook, and the most recent version is available online:

* Sutton/Barto "Reinforcement Learning: An Introduction": http://incompleteideas.net/sutton/book/bookdraft2017june.pdf

## Teams

A large portion of new research is being produced by a handful of groups:

* University of Alberta: http://spaces.facsci.ualberta.ca/rlai/
* DeepMind: https://deepmind.com/
* OpenAI: https://openai.com/
* Berkeley: http://bair.berkeley.edu/


## Courses

* David Silver (UCL) "Reinforcement Learning": http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html 
* Sergey Levine, John Schulman, Chelsea Finn (Berkeley) "Deep Reinforcement Learning": http://rll.berkeley.edu/deeprlcoursesp17/ (also see: https://berkeley-deep-learning.github.io/)
* Katerina Fragkiadaki, Ruslan Satakhutdinov (CMU) "Deep Reinforcement Learning and Control": https://katefvision.github.io/


## Tutorials

* David Silver, Deep Reinforcement Learning tutorial (ICML 2016): http://icml.cc/2016/tutorials/deep_rl_tutorial.pdf
* John Shulman, Deep Reinforcement Learning tutorial (Deep Learning School 2016): https://www.youtube.com/watch?v=PtAIh9KSnjo
* Pieter Abbeel, Deep Reinforcement Learning: https://simons.berkeley.edu/talks/pieter-abbeel-2017-3-28


## General Discussion

* Li (2017) "Deep Reinforcement Learning: An Overview" https://arxiv.org/abs/1701.07274
* Arulkumaran (2017) "A Brief Survey of Deep Reinforcement Learning" https://arxiv.org/abs/1708.05866


## Blog Posts

* Andrej Karpathy "Pong From Pixels" http://karpathy.github.io/2016/05/31/rl/
* Arthur Juliani, 8-Part Series on "Reinforcement Learning with Tensorflow": 
	* [Part 0 — Q-Learning Agents](https://medium.com/@awjuliani/simple-reinforcement-learning-with-tensorflow-part-0-q-learning-with-tables-and-neural-networks-d195264329d0)
	* [Part 1 — Two-Armed Bandit](https://medium.com/@awjuliani/super-simple-reinforcement-learning-tutorial-part-1-fd544fab149)
	* [Part 1.5 — Contextual Bandits](https://medium.com/@awjuliani/simple-reinforcement-learning-with-tensorflow-part-1-5-contextual-bandits-bff01d1aad9c#.uzs1axw0s)
	* [Part 2 — Policy-Based Agents](https://medium.com/@awjuliani/super-simple-reinforcement-learning-tutorial-part-2-ded33892c724)
	* [Part 3 — Model-Based RL](https://medium.com/@awjuliani/simple-reinforcement-learning-with-tensorflow-part-3-model-based-rl-9a6fe0cce99)
	* [Part 4 — Deep Q-Networks and Beyond](https://medium.com/@awjuliani/simple-reinforcement-learning-with-tensorflow-part-4-deep-q-networks-and-beyond-8438a3e2b8df#.i2zpbmre8)
	* [Part 5 — Visualizing an Agent’s Thoughts and Actions](https://medium.com/@awjuliani/simple-reinforcement-learning-with-tensorflow-part-5-visualizing-an-agents-thoughts-and-actions-4f27b134bb2a)
	* [Part 6 — Partial Observability and Deep Recurrent Q-Networks](https://medium.com/emergent-future/simple-reinforcement-learning-with-tensorflow-part-6-partial-observability-and-deep-recurrent-q-68463e9aeefc#.9djtshpqo)
	* [Part 7 — Action-Selection Strategies for Exploration](https://medium.com/emergent-future/simple-reinforcement-learning-with-tensorflow-part-7-action-selection-strategies-for-exploration-d3a97b7cceaf#.qfg7lqxpr)
	* [Part 8 — Asynchronous Actor-Critic Agents (A3C)](https://medium.com/emergent-future/simple-reinforcement-learning-with-tensorflow-part-8-asynchronous-actor-critic-agents-a3c-c88f72a5e9f2)


## Tools

* OpenAI: https://openai.com/systems/


## Benchmarks/Data

* Deep Learning: http://deeplearning.net/datasets/
* MNIST: http://yann.lecun.com/exdb/mnist/
* ImageNet: http://image-net.org/challenges/LSVRC/2017/
* OpenAI gym: https://github.com/openai/gym
* OpenAI universe: https://github.com/openai/universe



## RL Resources

* https://github.com/aikorea/awesome-rl



## Source Code and Baselines

* https://deepmind.com/research/open-source/open-source-code/
* Denny Britz, "Learning Reinforcement Learning" (with Code, Exercises and Solutions: http://www.wildml.com/2016/10/learning-reinforcement-learning/


## Models

OpenAI's "baselines" provides some nice implementations of different state-of-the-art (SOTA) agent models:

* https://github.com/openai/baselines
* https://blog.openai.com/openai-baselines-dqn/
* https://blog.openai.com/baselines-acktr-a2c/


### Deep Q-Networks (DQN) (2015)

* Mnih et. al. (DeepMind) "Human-level control through deep reinforcement learning" (2015) http://www.nature.com/nature/journal/v518/n7540/full/nature14236.html
* Source code from DeepMind: https://sites.google.com/a/deepmind.com/dqn/
* https://github.com/devsisters/DQN-tensorflow
* https://github.com/tmulc18/TensorFlow-FlappyBird



### Trust Region Policy Optimization (2015)

* Schulman et. al. (Berkeley) "Trust Region Policy Optimization" (2015) https://arxiv.org/abs/1502.05477



### Asynchronous Advantage Actor-Critic (A3C) (2016)

* Paper: Mnih et. al. (DeepMind/Montreal) "Asynchronous Methods for Deep Reinforcement Learning" (2016) https://arxiv.org/abs/1602.01783
* A3C example from OpenAI: https://github.com/openai/universe-starter-agent


### Neural Episodic Control (2017)

* Pritzel et. al. (DeepMind) "Neural Episodic Control" (2017) https://arxiv.org/abs/1703.01988
* https://github.com/ShibiHe/Model-Free-Episodic-Control
* https://github.com/mjacar/pytorch-nec
* https://github.com/EndingCredits/Neural-Episodic-Control


### Evolutionary Strategies (2017)

* Salimans et. al. (OpenAI) "Evolution Strategies as a Scalable Alternative to Reinforcement Learning" (2017) https://arxiv.org/abs/1703.03864
* OpenAI Blog Post: https://blog.openai.com/evolution-strategies/
* https://github.com/openai/evolution-strategies-starter
* https://github.com/alirezamika/bipedal-es



## Other

* CS231n: Convolutional Neural Networks for Visual Recognition: http://cs231n.github.io/


## Games

* General Game Playing course at Stanford: http://arrogant.stanford.edu/ggp/homepage/notes.php
* Description of DeepBlue: http://stanford.edu/~cpiech/cs221/apps/deepBlue.html

