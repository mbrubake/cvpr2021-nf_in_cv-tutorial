---
layout: default
---

This half-day CVPR 2021 tutorial will cover Normalizing Flows and Invertible Neural Networks with a specific focus on applications in computer vision.


### Background 

Normalizing flows (NFs) offer an answer to a long-standing question in computer vision: 
How can one define faithful probabilistic models for complex high-dimensional data like natural images?
NFs solve this problem by means of non-linear bijective mappings from simple distributions (e.g. multivariate normal) to the desired target distributions.
These mappings are implemented with invertible neural networks and thus have high expressive power and can be trained by gradient descent in the usual way.
Thanks to bijectivity, NFs can work forward and backward, serving as both discriminative and generative models alike, and are especially suitable for inverse problems.
This tutorial will explain the theoretical underpinnings of NFs, show various practical implementation options, clarify their relationships with GANs, VAEs, and non-linear ICA.
Particular emphasis will be given to successful applications in the field of computer vision.


### Target Audience

The tutorial is intended to be introductory, i.e., aimed at people with basic backgrounds in ML/CV who are interested in applying these methods in related problems.


### Schedule

The tutorial will be held in the morning tutorial session on June 20, 2021 as a live, interactive lecture on Zoom and is available to registered CVPR attendees only.  The Zoom link will be available through the CVPR online platform.  The schedule below is tentative and subject to revision.  Times are in Eastern Daylight Time (UTC/GMT-4).

| Time (EDT/UTC-4) | Title                                                                            | Presenter       |
|------------------|----------------------------------------------------------------------------------|-----------------|
| 10am-11am        | Welcome and Introduction to Normalizing Flows                                    | Marcus Brubaker |
| 11am-noon        | Examples of Normalizing Flows in Computer Vision:<br>Wavelet Flow and Noise Flow | Marcus Brubaker |
| noon-2pm         | Invertible Neural Networks in Computer Vision and Science                        | Ullrich Köthe   |
|------------------|----------------------------------------------------------------------------------|-----------------|

### Recordings and Slides

A complete recording of the live tutorial session is available on [YouTube here](https://youtu.be/8XufsgG066A).  Slides are available below:
- [Introduction to Normalizing Flows](Introduction - CVPR2021.pdf) by Marcus Brubaker
- [Examples of Normalizing Flows in Computer Vision: Noise Flow and Wavelet Flow](Noise Flow and Wavelet Flow - CVPR2021.pdf) by Marcus Brubaker
- [Invertible Neural Networks in Computer Vision and Science](INNs-CVPR-June-2021.pdf) by Ullrich Köthe

### References
- [Normalizing Flows: An Introduction and Review of Current Methods](https://arxiv.org/abs/1908.09257) by Ivan Kobyzev, Simon J.D. Prince and Marcus A. Brubaker. IEEE PAMI, 2020.

### Organizers
- [**Marcus A. Brubaker**](https://mbrubake.github.io) Assistant Professor, York University, Canada
- [**Ullrich Köthe**](https://hci.iwr.uni-heidelberg.de/vislearn/people/ullrich-koethe/) Professor, University of Heidelberg, Germany
