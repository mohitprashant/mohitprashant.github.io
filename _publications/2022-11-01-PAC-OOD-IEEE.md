---
title: "PAC-Based Formal Verification for Out-of-Distribution Data Detection"
collection: publications
category: manuscripts
permalink: /publication/2022-11-01-PAC-OOD-IEEE
excerpt: 'We present a technique for detecting OOD instances in autonomous driving with PAC guarantees.'
date: 2022-11-01
venue: 'IEEE International Conference on System Reliability and Safety'
paperurl: 'https://mohitprashant.github.io/files/ICSRS2022.pdf'
citation: 'Prashant, Mohit, and Arvind Easwaran. &quot;PAC-Based Formal Verification for Out-of-Distribution Data Detection.&quot; <i>2022 6th International Conference on System Reliability and Safety (ICSRS)</i>. IEEE, 2022.'
---

Cyber-physical systems (CPS) like autonomous vehicles, that utilize learning components, are often sensitive to noise and out-of-distribution (OOD) instances encountered during run-time. As such, safety critical tasks depend upon OOD detection subsystems in order to restore the CPS to a known state or interrupt execution to prevent safety from being compromised. However, it is difficult to guarantee the performance of OOD detectors as it is difficult to characterize the OOD aspect of an instance, especially in high-dimensional unstructured data.To distinguish between OOD data and data known to the learning component through the training process, an emerging technique is to incorporate variational autoencoders (VAE) within systems and apply classification or anomaly detection techniques on their latent spaces. The rationale for doing so is the reduction of the data domain size through the encoding process, which benefits real-time systems through decreased processing requirements, facilitates feature analysis for unstructured data and allows more explainable techniques to be implemented.This study places probably approximately correct (PAC) based guarantees on OOD detection using the encoding process within VAEs to quantify image features and apply conformal constraints over them. This is used to bound the detection error on unfamiliar instances, ϵ, with user-defined confidence, 1 − δ. The approach used in this study is to empirically establish these bounds by sampling the latent probability distribution and evaluating the error with respect to the constraint violations that are encountered. The guarantee is then verified using data generated from CARLA, an open-source driving simulator.