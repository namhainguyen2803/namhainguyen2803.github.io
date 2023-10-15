---
layout: about
title: About
permalink: /
subtitle: Ph.D. Student at <a href='https://stat.utexas.edu/'>Department of Statistics and Data Sciences</a>, <a href='https://www.utexas.edu/'>University of Texas at Austin</a> 

profile:
  align: right
  image: khai2.png
  image_circular: false # crops the image to make it circular
  address: >
   

news: true  # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

Hi! I’m Khai, a third-year Ph.D. student at [Department of Statistics and Data Sciences](https://stat.utexas.edu/), [University of Texas at Austin](https://www.utexas.edu/). I am fortunate to be advised by Professor [Nhat Ho](https://nhatptnk8912.github.io/) and to be associated with Institute for Foundations of Machine Learning ([IFML](https://www.ifml.institute/)). I am visiting student at [Statistical Information Lab](https://odin.mdacc.tmc.edu/~wwang7/people.html) at [The University of Texas MD Anderson Cancer Center](https://www.mdanderson.org/). I graduated from  [Hanoi University of Science and Technology](https://soict.hust.edu.vn/) with a Computer Science Bachelor's degree.
Before joining UT Austin, I was an AI Research Resident at [VinAI Research](http://www.vinai.io) under the supervision of [Dr. Hung Bui](https://sites.google.com/site/buihhung/).

**Research:** My current works are making [Optimal Transport](https://en.wikipedia.org/wiki/Transportation_theory_(mathematics)) scalable in statistical inference (low time complexity, low space complexity, low sample complexity) via the one-dimensional projection approach which is known as sliced optimal transport (sliced Wasserstein distance). 


My works focus on three aspects of the SW distance:
* ***Slicing distributions.*** The vanilla sliced Wasserstein (SW) distance naively treats all one-dimensional projections the same and independently by using the uniform distribution over projecting directions. To improve and generalize the SW, I propose to search for the best distribution over projecting distributions (or the slicing distribution) which can maximize the expected projected distance. 
In particular, a regularized implicit family of distributions is introduced in [[ICLR'21]](https://arxiv.org/pdf/2002.07367.pdf) and  explicit families (von Mises-Fisher and Power Spherical) are introduced in [[ICLR'21]](https://arxiv.org/pdf/2010.01787.pdf). Moreover, I introduce the usage of
amortized optimization to predict the optimal slicing distribution given two input probablity measures in the setting which has various pairs of probability measures in [[NeurIPS'22]](https://arxiv.org/pdf/2203.13417.pdf) and [[ICML'23]](https://arxiv.org/pdf/2301.04791.pdf). To enhance further the quality of projecting directions, I break the independence between them by imposing the first order Markov structure in [[NeurIPS'23]](https://arxiv.org/pdf/2301.03749.pdf). 
To avoid unstable optimization and model misspecification in designing slicing model, I propose energy-based slicing distribution  that is parameter-free and has the density proportional to an energy function of the projected one-dimensional Wasserstein distance in [[NeurIPS'23](https://arxiv.org/pdf/2304.13586.pdf)].
* ***Projecting operators.*** The vanilla sliced Wasserstein distance utilizes the Radon Transform as the projecting operator. The Radon Transform simply takes the inner product between the supports of a probability measure
and  a projecting direction as the supports of the one-dimensional projected probability measure. To generalize the projecting operator to tensor spaces, I use convolution operator to project probability measures over tensors to one-dimension in [[NeurIPS'22]](https://arxiv.org/pdf/2204.01188.pdf). In addition, I connect deep learning (neural networks) techniques to sliced Wasserstein by proposing Overaparameterized Radon Transform and Hierarchical Radon Transform in [[ICLR'23]](https://arxiv.org/pdf/2209.13570.pdf). 
* ***Numerical approximation.*** The SW distance is usually estimated by Monte Carlo integration due to the intractable expectation with respect to the slicing distribution. To reduce the variance of the Monte Carlo estimator,
I first propose control variates which are based on the closed-form of the Wasserstein-2 distance between two Gaussians in [[Arxiv'23](https://arxiv.org/pdf/2305.00402.pdf)]. Importantly, the proposed control variates have linear time complexity and space complexity. In addition, we propose to use low-discrepancy sequences on the sphere (Quasi-Monte Carlo) to approximate sliced Wasserstein in [[Arxiv'23]](https://arxiv.org/pdf/2309.11713.pdf). Moreover, we propose Randomized Quasi-sliced Wasserstein unbiased estimation of sliced Wasserstein which are based on randomizing low-discrepancy sequences.

Moreover, I aim to push forward the application of optimal transport, Wasserstein distance, and sliced Wasserstein distance in probabilistic Machine Learning models such as  point-clouds applications [[ICML'23]](https://arxiv.org/pdf/2301.04791.pdf), 3D mesh deformation [[Arxiv'23]](https://arxiv.org/pdf/2305.17555.pdf), generative models [[NeurIPS'22]](https://arxiv.org/pdf/2203.13417.pdf), domain adaptation [[ICML'22]](https://proceedings.mlr.press/v162/nguyen22d/nguyen22d.pdf) [[ICML'22]](https://proceedings.mlr.press/v162/nguyen22e/nguyen22e.pdf), and other tasks that need to deal with probability measures.

