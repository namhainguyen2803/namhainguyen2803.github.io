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

Hi! I’m Khai, a second-year Ph.D. student at [Department of Statistics and Data Sciences](https://stat.utexas.edu/), [University of Texas at Austin](https://www.utexas.edu/), advised by Professor [Nhat Ho](https://nhatptnk8912.github.io/). I graduated from  [Hanoi University of Science and Technology](https://soict.hust.edu.vn/) with an excellent Computer Science Bachelor's degree.
Before joining UT Austin, I was an AI Research Resident at [VinAI Research, Vietnam](http://www.vinai.io) under the supervision of [Dr. Hung Bui](https://sites.google.com/site/buihhung/).

**Research:** My current works are making [Optimal Transport](https://en.wikipedia.org/wiki/Transportation_theory_(mathematics)) scalable in statistical inference (low computational complexity, low memory complexity, low sample complexity) via the one-dimensional projection approach which is known as sliced optimal transport (sliced Wasserstein distance). 

My works focus on pushing forward two directions:
* ***Selecting informative projecting directions***: The vanilla sliced Wasserstein distance naively treats all one-dimensional projections the same and independently by using the uniform distribution over projecting directions. To address the issue, I propose to search for the best distribution over projecting distributions (or the slicing distribution) which can maximize the expected projected distance. 
In particular, a regularized implicit family of distributions is introduced in [[ICLR'21]](https://openreview.net/pdf?id=QYjO70ACDK) and  explicit families (von Mises-Fisher and Power Spherical) are introduced in [[ICLR'21]](https://openreview.net/pdf?id=DiQD7FWL233). Moreover, I introduce the usage of
amortized optimization to predict the optimal slicing distribution given two input probablity measures in the setting which has various pairs of probability measures in [[NeurIPS'22]](https://arxiv.org/pdf/2203.13417.pdf) and [[Arxiv'23]](https://arxiv.org/pdf/2301.04791.pdf). To enhance further the quality of projecting directions, I break the independence between them by imposing the first order Markov structure in [[Arxiv'23]](https://arxiv.org/pdf/2301.03749.pdf).
* ***Designing effective and efficient projecting operators***: The vanilla sliced Wasserstein distance utilizes the Radon Transform as the projecting operator. The Radon Transform simply takes the inner product between the supports of a probability measures
and  a projecting direction as the supports of the one-dimensional projected probability measures. To generalize the projecting operator to tensor spaces, I use convolution operator to project probability measures over tensors to one-dimension in [[NeurIPS'22]](https://arxiv.org/pdf/2204.01188.pdf). In addition, I connect deep learning (neural networks) techniques to sliced Wasserstein by proposing Overaparameterized Radon Transform and Hierarchical Radon Transform in [[ICLR'23]](https://arxiv.org/pdf/2209.13570.pdf). 

Moreover, I aim to push forward the application of optimal transport, Wasserstein distance, and sliced Wasserstein distance in probabilistic Machine Learning models such as  point-clouds applications [[Arxiv'23]](https://arxiv.org/pdf/2301.04791.pdf), generative models [[NeurIPS'22]](https://arxiv.org/pdf/2203.13417.pdf), domain adaptation [[ICML'22]](https://proceedings.mlr.press/v162/nguyen22d/nguyen22d.pdf) [[ICML'22]](https://proceedings.mlr.press/v162/nguyen22e/nguyen22e.pdf), and other tasks that need to deal with probability measures.

[comment]: <> (I am also interested in designing efficient [Transformer]&#40;https://en.wikipedia.org/wiki/Transformer_&#40;machine_learning_model&#41;&#41; architectures.)
