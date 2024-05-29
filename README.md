# RLHF
Reinforcement learning with human feedback loop
In the context of language models, the policy $\pi$ is represented by the language model, which estimates the probability distribution over possible actions (words or tokens) given the current state (the sequence of previously generated words or tokens). Mathematically, this can be expressed as:

$\ \pi(a_t \mid s_t) = P(a_t \mid s_t; \theta) \$

where:
- $\pi(a_t \mid s_t)$ is the policy's probability of taking action $a_t$ (generating the next word or token) given the state $s_t$ (the current sequence of words or tokens).
- $P(a_t \mid s_t; \theta)$ is the probability of $a_t$ given $s_t$ as modeled by the language model with parameters $\theta$.
