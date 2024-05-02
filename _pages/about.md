---
layout: about
title: About
permalink: /
subtitle: Ph.D. Candidate at <a href='https://stat.utexas.edu/'>Department of Statistics and Data Sciences</a>, <a href='https://www.utexas.edu/'>University of Texas at Austin</a> 

profile:
  align: right
  image: khai2.png
  image_circular: false # crops the image to make it circular
  address: >
   

news: true  # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

Hi! I’m Khai, a third-year Ph.D. candidate at [Department of Statistics and Data Sciences](https://stat.utexas.edu/), [University of Texas at Austin](https://www.utexas.edu/). I am fortunate to be advised by Professor [Nhat Ho](https://nhatptnk8912.github.io/) and Professor 
[Peter Müller](https://www.ma.utexas.edu/component/cobalt/item/15-mathematics/364-mueller-peter?Itemid=1259). I am associated with Institute for Foundations of Machine Learning ([IFML](https://www.ifml.institute/)) and I am a visiting student at [Statistical Information Lab](https://odin.mdacc.tmc.edu/~wwang7/people.html) at [The University of Texas MD Anderson Cancer Center](https://www.mdanderson.org/). I graduated from  [Hanoi University of Science and Technology](https://soict.hust.edu.vn/) with a Computer Science Bachelor's degree.
Before joining UT Austin, I was an AI Research Resident at [VinAI Research](http://www.vinai.io) under the supervision of [Dr. Hung Bui](https://sites.google.com/site/buihhung/).



**Research:** My current works are making [Optimal Transport](https://en.wikipedia.org/wiki/Transportation_theory_(mathematics)) scalable in statistical inference (low time complexity, low space complexity, low sample complexity) via the one-dimensional projection approach which is known as sliced optimal transport (sliced Wasserstein distance). 

<details>
<summary> <b> Research Summary</b></summary>
<br>
My works focus on three aspects of the SW distance:
<br>
<br>
<b> <i>Slicing distributions.</i></b> The vanilla sliced Wasserstein (SW) distance naively treats all one-dimensional projections the same and independently by using the uniform distribution over projecting directions. To improve and generalize the SW, I propose to search for the best distribution over projecting distributions (or the slicing distribution) which can maximize the expected projected distance. 
In particular, a regularized implicit family of distributions is introduced in <a href="https://arxiv.org/pdf/2002.07367.pdf">[ICLR'21]</a> and  explicit families (von Mises-Fisher and Power Spherical) are introduced in <a href="https://arxiv.org/pdf/2010.01787.pdf">[ICLR'21]</a>. Moreover, I introduce the usage of
amortized optimization to predict the optimal slicing distribution given two input probability measures in the setting which has various pairs of probability measures in <a href="https://arxiv.org/pdf/2203.13417.pdf">[NeurIPS'22]</a> and <a href="https://arxiv.org/pdf/2301.04791.pdf">[ICML'23]</a>. To enhance further the quality of projecting directions, I break the independence between them by imposing the first order Markov structure in <a href="https://arxiv.org/pdf/2301.03749.pdf">[NeurIPS'23]</a>. 
To avoid unstable optimization and model misspecification in designing slicing model, I propose the energy-based slicing distribution  that is parameter-free and has the density proportional to an energy function of the projected one-dimensional Wasserstein distance in <a href="https://arxiv.org/pdf/2304.13586.pdf">[NeurIPS'23]</a>. To push forward further the optimization-free direction, I propose the random-path projecting direction in <a href="https://arxiv.org/pdf/2401.15889.pdf">[ICML'24]</a>.
<br>
<br>
<b> <i>Projecting operators.</i></b> The vanilla sliced Wasserstein distance utilizes the Radon Transform as the projecting operator. The Radon Transform simply takes the inner product between the supports of a probability measure
and  a projecting direction as the supports of the one-dimensional projected probability measure. To generalize the projecting operator to tensor spaces, I use the convolution operator to project probability measures over tensors to one-dimension in <a href="https://arxiv.org/pdf/2204.01188.pdf">[NeurIPS'22]</a>. In addition, I connect deep learning (neural networks) techniques to sliced Wasserstein by proposing Overaparameterized Radon Transform and Hierarchical Radon Transform in <a href="https://arxiv.org/pdf/2209.13570.pdf">[ICLR'23]]</a>. Recently, I proposed hierarchical hybrid Radon Transform and hierarchical hybrid sliced Wasserstein distance for dealing with heterogeneous joint distributions in <a href="https://arxiv.org/pdf/2404.15378.pdf">[Arxiv'24]]</a>.
<br>
<br>
<b> <i>Numerical approximation.</i></b>  The SW distance is usually estimated by Monte Carlo integration due to the intractable expectation with respect to the slicing distribution. To reduce the variance of the Monte Carlo estimator,
I first propose control variates which are based on the closed-form of the Wasserstein-2 distance between two Gaussians in <a href="https://arxiv.org/pdf/2305.00402.pdf">[ICLR'24]</a>. Importantly, the proposed control variates have linear time complexity and space complexity. In addition, I propose to use low-discrepancy sequences on the sphere (Quasi-Monte Carlo) to approximate sliced Wasserstein in <a href="https://arxiv.org/pdf/2309.11713.pdf">[ICLR'24]</a>. Moreover, we propose Randomized Quasi-sliced Wasserstein, an unbiased estimation of sliced Wasserstein which are based on randomizing low-discrepancy sequences.
<br>
<br>
Moreover, I aim to push forward the <b> <i>application</i></b> of optimal transport, Wasserstein distance, and sliced Wasserstein distance in probabilistic Machine Learning models such as  point-clouds applications <a href="https://arxiv.org/pdf/2301.04791.pdf">[ICML'23]</a>, 3D mesh deformation <a href="https://arxiv.org/pdf/2305.17555.pdf">[ICLR'24]</a>, generative models (GANs, Diffusion Models) <a href="https://arxiv.org/pdf/2203.13417.pdf">[NeurIPS'22]</a> <a href="https://arxiv.org/pdf/2401.15889.pdf">[Arxiv'24]</a>, domain adaptation <a href="https://proceedings.mlr.press/v162/nguyen22d/nguyen22d.pdf">[ICML'22]</a>, <a href="https://proceedings.mlr.press/v162/nguyen22e/nguyen22e.pdf">[ICML'22]</a>, multimodal representation learning <a href="https://openreview.net/pdf?id=l60EM8md3t">[ICLR'24]</a>, 3D shape correspondence learning <a href="https://openreview.net/pdf?id=lz8a6ThNOi">[CVPR'24]</a>, and other tasks that need to deal with probability measures.
</details>
<br>