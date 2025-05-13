---
title: "ML Safety and Learning Theory"
collection: teaching
type: "Postgraduate Research Workshops"
permalink: /teaching/mlsafety
venue: "-"
date: 2025-08-01
location: "-"
---

Conducting a series of online and in-person workshops on ML safety and learning theory using [probably approximately correct guarantees](https://en.wikipedia.org/wiki/Probably_approximately_correct_learning).
The aim of these workshops is to introduce the listener to the notion of error-confidence bounds within ML and demonstrate practical applications of learning theory in deriving safety guarantees for learning-enabled systems.



Presentation Slides
======
The presentation slides used in these workshops are available [here](https://mohitprashant.github.io/talks/)


PAC Guarantees
======
These workshops are divided into multiple parts: (1) guarantees set during the learning process and (2) post-training verification.


Guarantees Apriori
======
We take a more theoretical approach at placing bounds on the learning process based on the expected training distribution and the expected information yield of new samples with respect to training time. This allows us to bound the sample-complexity of training using error-confidence parameters.


Post-Training Verification
======
We take a more empirical approach at placing bounds on the outcome of training using a monte-carlo sampling based process and optimize using [scenario based approaches](https://link.springer.com/article/10.1007/s10107-024-02074-3) to to find error given a confidence value.
