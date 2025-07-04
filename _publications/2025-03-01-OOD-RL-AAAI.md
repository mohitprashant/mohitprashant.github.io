---
title: "Guaranteeing Out-Of-Distribution Detection in Deep RL via Transition Estimation"
collection: publications
category: manuscripts
permalink: /publication/2025-03-01-OOD-RL-AAAI
excerpt: 'We provide a basis for defining out-of-distribution execution in RL and provide a framework for detection with guarantees.'
date: 2025-03-01
venue: 'Proceedings of the AAAI Conference on Artificial Intelligence'
paperurl: 'https://mohitprashant.github.io/files/AAAI2025.pdf'
citation: 'Prashant, Mohit, et al. &quot;Guaranteeing Out-Of-Distribution Detection in Deep RL via Transition Estimation&quot;. <i>Proceedings of the AAAI Conference on Artificial Intelligence</i>. Vol. 39. No. 12. 2025.'
---

An issue concerning the use of deep reinforcement learning (RL) agents is whether they can be trusted to perform reliably when deployed, as training environments may not reflect real-life environments. Anticipating instances outside their training scope, learning-enabled systems are often equipped with out-of-distribution (OOD) detectors that alert when a trained system encounters a state it does not recognize or in which it exhibits uncertainty. There exists limited work conducted on the problem of OOD detection within RL, with prior studies being unable to achieve a consensus on the definition of OOD execution within the context of RL. By framing our problem using a Markov Decision Process, we assume there is a transition distribution mapping each state-action pair to another state with some probability. Based on this, we consider the following definition of OOD execution within RL: A transition is OOD if its probability during real-life deployment differs from the transition distribution encountered during training. As such, we utilize conditional variational autoencoders (CVAE) to approximate the transition dynamics of the training environment and implement a conformity-based detector using reconstruction loss that is able to guarantee OOD detection with a pre-determined confidence level. We evaluate our detector by adapting existing benchmarks and compare it with existing OOD detection models for RL.
