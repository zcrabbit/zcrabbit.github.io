---
layout: page
title: Statistical Models & Computing Methods, Fall 2020
author: Cheng Zhang
---


### Basic Info
- Instructor: Cheng Zhang (<chengzhang@math.pku.edu.cn>)
- Class times: Thursday 6:40-9:30pm, Classroom Building No.2, Room 401  
- Office hours: Thursday 3:00-5:00pm or by appointment, 1279 Science Building No.1
- [Syllabus]({{sites.baseurl}}/courses/Syllabus-smcm-f20.pdf)

### Description and Objectives
Computational statistics is a branch of mathematical sciences focusing on efficient numerical methods for statistical problems. The goal of this course is to provide students an introduction to a variety of modern statistical models and related computing methods. Topics include numerical optimization in statistical inference including expectation-maximization (EM) algorithm, Fisher scoring, gradient descent and stochastic gradient descent, etc., numerical integration approaches include basic numerical quadrature and Monte Carlo methods, and approximate Bayesian inference methods including Markov chain Monte Carlo, variational inference and their scalable counterparts, with applications in statistical machine learning, computational biology and other related fields. Additional topics may vary. Coursework will include computer assignments.

### Prerequisites
Multivariate calculus, linear algebra, graduate level courses in probability and statistics, applied stochastic processes

### Recommended Textbooks
- Givens, G. H. and Hoeting, J. A. (2005) Computational Statistics, 2nd Edition, Wiley-Interscience.
- Gelman, A., Carlin, J., Stern, H., and Rubin, D. (2003). Bayesian Data Analysis, 2nd Edition, Chapman & Hall.
- Liu, J. (2001). Monte Carlo Strategies in Scientific Computing, Springer-Verlag.
- Lange, K. (2002). Numerical Analysis for Statisticians, Springer-Verlag, 2nd Edition.
- Hastie, T., Tibshirani, R. and Friedman, J. (2009). The Elements of Statistical Learning, 2nd Edition, Springer.
- Goodfellow, I., Bengio, Y. and Courville, A. (2016). Deep Learning, MIT Press.

### Grading
- Homework (60%): 4 problem sets (15% each)
- final project (40%): midterm proposal (5%) + oral presentation (10%) + final write-up (25%)

There will be `7` free late days in total, use them in your own ways. Afterwards, late homework will be discounted by 25% for each additional day. Not acceptable after `3` late days per problem set (PS). Late policy `does not apply` to the final project, please submit it on time. Discussing assignments verbally with your classmates is allowed and encouraged. However, you should finish your work independently. Identified cheating incidents will be reported and will result in zero grades.

### Computer and Technical Requirements

We will use python during the course. A good Python tutorial is available at <http://www.scipy-lectures.org/>. You may also find another shorter tutorial useful at <http://cs231n.github.io/python-numpy-tutorial/>. If you have never used Python before, I recommend using Anaconda Python 3.7 <https://www.continuum.io/>.

### Lectures
- 09/24/2020: [Lecture 1 - Introduction]({{sites.baseurl}}/static/slides/smcm_fall20/lec01.pdf)  
  Textbook on convex optimization: <https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf>
- 10/15/2020: [Lecture 2 - Gradient Methods]({{sites.baseurl}}/static/slides/smcm_fall20/lec02.pdf)
- 10/22/2020: [Lecture 3 - Numerical Integration]({{sites.baseurl}}/static/slides/smcm_fall20/lec03.pdf)
- 10/29/2020: [Lecture 4 - Markov Chain Monte Carlo]({{sites.baseurl}}/static/slides/smcm_fall20/lec04.pdf)  
  Handbook of Markov Chain Monte Carlo: <https://www.mcmchandbook.net>
- 11/05/2020: [Lecture 5 - Advanced MCMC]({{sites.baseurl}}/static/slides/smcm_fall20/lec05.pdf)
- 11/12/2020: [Lecture 6 - Scalable MCMC]({{sites.baseurl}}/static/slides/smcm_fall20/lec06.pdf)
- 11/19/2020: [Lecture 7 - Expectation Maximization]({{sites.baseurl}}/static/slides/smcm_fall20/lec07.pdf)
- 11/26/2020: [Lecture 8 - Variational Inference]({{sites.baseurl}}/static/slides/smcm_fall20/lec08.pdf)
- 12/03/2020: [Lecture 9 - Stochastic Variational Inferece and Alternative Training Objectives]({{sites.baseurl}}/static/slides/smcm_fall20/lec09.pdf)
- 12/10/2020: [Lecture 10 - Advanced VI]({{sites.baseurl}}/static/slides/smcm_fall20/lec10.pdf)
- 12/17/2020: [Lecture 11 - Autoregressive Models and Variational Autoencoders]({{sites.baseurl}}/static/slides/smcm_fall20/lec11.pdf)
- 12/24/2020: [Lecture 12 - Generative Adversarial Nets and Bayesian Phylogenetic Inference]({{sites.baseurl}}/static/slides/smcm_fall20/lec12.pdf)


### Assignments
- 10/15/2020: [Homework 1]({{sites.baseurl}}/static/slides/smcm_fall20/hw01.pdf), **Due** `10/29/2020`
- 11/05/2020: [Homework 2]({{sites.baseurl}}/static/slides/smcm_fall20/hw02.pdf), **Due** `11/19/2020` &nbsp; Data: [p3]({{sites.baseurl}}/static/datasets/mcs_hw2_p3_data.npy)
- 11/25/2020: [Homework 3]({{sites.baseurl}}/static/slides/smcm_fall20/hw03.pdf), **Due** `12/10/2020` &nbsp; Data: [p2]({{sites.baseurl}}/static/datasets/mog_data.npy), [p3]({{sites.baseurl}}/static/datasets/proteins.zip)
- 12/17/2020: [Homework 4]({{sites.baseurl}}/static/slides/smcm_fall20/hw04.pdf), **Due** `01/07/2021` &nbsp; Data: [p1]({{sites.baseurl}}/static/datasets/mcs_hw4_p1_lda.npy), [p3]({{sites.baseurl}}/static/datasets/banana_shape_data.npy)

### Final Project
You may structure your project exploration around a general problem type, algorithm, or data set, but should explore around your problem, testing thoroughly or comparing to alternatives. You may work on the project as teams. Each team may have up to `4` people. Please form your team by the end the `4th` week. You should present a project proposal that briefly describe your project concept and goals in one slide on `11/12`. You should turn in a write-up (< 10 pages) describing your project and its outcomes, similar to a research-level publication. I suggest the latex styles for [NeurIPS](https://nips.cc/Conferences/2019/PaperInformation/StyleFiles) or [ICLR](https://iclr.cc/Conferences/2019/CallForPapers). There will be in class project presentation at the end of the term. Not presenting your projects will be taken as voluntarily `giving up` the opportunity for the final write-ups.

### Tentative Schedule

| Week  | Date | Topics       |    Notes   |
| ----- |------| -----        |   -----    |
| 1     |09/24 | Introduction, Convex Optimization|            |
| 2     |10/01 | -- | National Day  |
| 3     |10/08 | -- | National Day  | 
| 4     |10/15 | Iterative Reweighted Least Squares, Gradient Descent Methods|   |
| 5     |10/22 | Numerical Quadrature, Monte Carlo Methods, Variance Reduction Techniques|   |
| 6     |10/29 | Markov Chain Monte Carlo, Improving Mixing and Convergence|     |
| 7     |11/05 | Auxiliary Variable Methods, Hamiltonian Monte Carlo, Adaptive MCMC|     |
| 8     |11/12 | Scalable MCMC Methods  |  `Proposal Presentation`  |
| 9     |11/19 | Expectation Maximization, Convergence Theory and EM Variants |       |     
| 10    |11/26 | Variational Bayesian EM, Variational Inference, Mean Field VI |      |
| 11    |12/03 | Stochastic Variational Inference, Choice of Training Objectives|      |
| 12    |12/10 | Normalizing Flow, Combinig VI and MCMC |          |
| 13    |12/17 | Autoregressive Models, Variational Autoencoder |       |
| 14    |12/24 | Generative Adversarial Networks, Bayesian Phylogenetic Inference |     |
| 15    |12/31 | Project Presentation  |    |
| 16    |01/07 | Project Presentation  |    |