---
title: "Improving Reinforcement Learning Sample-Efficiency using Local Approximation"
collection: publications
category: manuscripts
permalink: /publication/2025-10-01-Local-Approx-ECAI
excerpt: 'We provide tighter sample-complexity bounds for reinforcement learning on metric spaces through local approximation and provide a respective algorithm for more efficient learning.'
date: 2025-03-01
venue: 'Proceedings of the ECAI Conference on Artificial Intelligence'
paperurl: 'TBP'
citation: 'Preprint'
---

In this study, we derive Probably Approximately Correct (PAC) bounds on the asymptotic sample-complexity for RL within the infinite-horizon Markov Decision Process (MDP) setting that are sharper than those in existing literature. The premise of our study is twofold: firstly, the further two states are from each other, transitionwise,
the less relevant the value of the first state is when learning the 𝜖-optimal value of the second; secondly, the amount of ’effort’, sample-complexity-wise, expended in learning the 𝜖-optimal value of a state is independent of the number of samples required to learn the 𝜖-optimal value of a second state that is a sufficient number of
transitions away from the first. Inversely, states within each other’s vicinity have values that are dependent on each other and will require a similar number of samples to learn. By approximating the original MDP using smaller MDPs constructed using subsets of the
original’s state-space, we are able to reduce the sample-complexity by a logarithmic factor to 𝑂(𝑆𝐴 log𝐴) timesteps, where 𝑆 and 𝐴 are the state and action space sizes. We are able to extend these results to an infinite-horizon, model-free setting by constructing a PAC-MDP algorithm with the aforementioned sample-complexity. We conclude by showing how significant the improvement is by comparing our algorithm with prior work in an experimental setting.