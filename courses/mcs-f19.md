---
layout: page
title: Modern Computational Statistics, Fall 2019
author: Cheng Zhang
---

[Syllabus]({{sites.baseurl}}/courses/Syllabus.pdf)

### Basic Info
- Instructor: Cheng Zhang (<chengzhang@math.pku.edu.cn>)
- Class times: Monday 6:40-8:30pm, odd Wednesday 8:00-9:50am, Classroom Building No.3, Room 504  
- Office hours: Thursday 3:00-5:00pm or by appointment, 1279 Science Building No.1
- Piazza: <https://piazza.com/peking_university/fall2019/00113730>
  
### Description and Objectives
Computational statistics is a branch of mathematical sciences focusing on efficient numerical methods for problems arising in statistics. The goal of this course is to provide students an introduction to a variety of modern computational statistical techniques and the role of computation as a tool of discovery. Topics include numerical optimization in statistical inference including expectation-maximization (EM) algorithm, Fisher scoring, gradient descent and stochastic gradient descent, etc., numerical integration approaches include basic numerical quadrature and Monte Carlo methods, and approximate Bayesian inference methods including Markov chain Monte Carlo, variational inference and their scalable counterparts, with applications in statistical machine learning, computational biology and other related fields. Additional topics may vary. Coursework will include computer assignments.

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
- 4 problem sets (15% each), 60%
- final project (40%): midterm proposal (5%) + final write-up (35%)

There will be `7` free late days in total, use them in your own ways. Afterwards, late homework will be discounted by 25% for each additional day. Not acceptable after `3` late days per problem set (PS). Late policy `does not apply` to the final project, please submit it on time. Discussing assignments verbally with your classmates is allowed and encouraged. However, you should finish your work independently. Identified cheating incidents will be reported and will result in zero grades.

### Computer and Technical Requirements

We will use python during the course. A good Python tutorial is available at <http://www.scipy-lectures.org/>. You may also find another shorter tutorial useful at <http://cs231n.github.io/python-numpy-tutorial/>. If you have never used Python before, I recommend using Anaconda Python 3.7 <https://www.continuum.io/>.

### Lectures
- 09/09/2019: [Lecture 1 - Introduction]({{sites.baseurl}}/static/slides/mcs_fall19/lec01.pdf)
- 09/11/2019: [Lecture 2 - Optimization]({{sites.baseurl}}/static/slides/mcs_fall19/lec02.pdf)  
  Textbook on convex optimization: <https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf>
- 09/16/2019: [Lecture 3 - Advanced Gradient Methods]({{sites.baseurl}}/static/slides/mcs_fall19/lec03.pdf)
- 09/23/2019: [Lecture 4 - Numerical Integration]({{sites.baseurl}}/static/slides/mcs_fall19/lec04.pdf)
- 09/25/2019: [Lecture 5 - Advanced Monte Carlo]({{sites.baseurl}}/static/slides/mcs_fall19/lec05.pdf)
- 10/07/2019, 10/09/2019: [Lecture 6, 7 - Markov Chain Monte Carlo]({{sites.baseurl}}/static/slides/mcs_fall19/lec0607.pdf)  
  Handbook of Markov Chain Monte Carlo: <https://www.mcmchandbook.net>
- 10/14/2019: [Lecture 8 - Advanced MCMC]({{sites.baseurl}}/static/slides/mcs_fall19/lec08.pdf)
- 10/21/2019: [Lecture 9 - Scalable MCMC]({{sites.baseurl}}/static/slides/mcs_fall19/lec09.pdf)
- 10/23/2019: [Lecture 10 - Expectation Maximization]({{sites.baseurl}}/static/slides/mcs_fall19/lec10.pdf)
- 10/28/2019: [Lecture 11 - Advanced EM]({{sites.baseurl}}/static/slides/mcs_fall19/lec11.pdf)
- 11/04/2019: [Lecture 12 - Variational EM]({{sites.baseurl}}/static/slides/mcs_fall19/lec12.pdf)
- 11/06/2019: [Lecture 13 - Variational Inference]({{sites.baseurl}}/static/slides/mcs_fall19/lec13.pdf)
- 11/11/2019: [Lecture 14 - Stochastic Variational Inference]({{sites.baseurl}}/static/slides/mcs_fall19/lec14.pdf)
- 11/18/2019: [Lecture 15 - Training Objectives in VI]({{sites.baseurl}}/static/slides/mcs_fall19/lec15.pdf)
- 11/20/2019: [Lecture 16 - Advanced VI]({{sites.baseurl}}/static/slides/mcs_fall19/lec16.pdf)
- 11/25/2019: [Lecture 17 - Autoregressive Models]({{sites.baseurl}}/static/slides/mcs_fall19/lec17.pdf)
- 12/02/2019: [Lecture 18 - Variational Autoencoder]({{sites.baseurl}}/static/slides/mcs_fall19/lec18.pdf)
- 12/04/2019: [Lecture 19 - Generative Adversarial Networks]({{sites.baseurl}}/static/slides/mcs_fall19/lec19.pdf)
- 12/09/2019: [Lecture 20 - Applications in Computational Biology]({{sites.baseurl}}/static/slides/mcs_fall19/lec20.pdf)



### Assignments
- 09/23/2019: [Homework 1]({{sites.baseurl}}/static/slides/mcs_fall19/hw01.pdf), **Due** `10/07/2019`
- 10/25/2019: [Homework 2]({{sites.baseurl}}/static/slides/mcs_fall19/hw02.pdf), **Due** `11/07/2019` &nbsp; Data: [p2]({{sites.baseurl}}/static/datasets/mcs_hw2_p2_data.npy), [p3]({{sites.baseurl}}/static/datasets/mcs_hw2_p3_data.npy)
- 11/16/2019: [Homework 3]({{sites.baseurl}}/static/slides/mcs_fall19/hw03.pdf), **Due** `12/02/2019`
- 12/02/2019: [Homework 4]({{sites.baseurl}}/static/slides/mcs_fall19/hw04.pdf), **Due** `12/16/2019` &nbsp; Data: [p1]({{sites.baseurl}}/static/datasets/mcs_hw4_p1_lda.npy)

### Final Project
You may structure your project exploration around a general problem type, algorithm, or data set, but should explore around your problem, testing thoroughly or comparing to alternatives. You may work on the project as teams. Each team may have 2-3 people. Please form your team by the end the 4th week. You should submit a project proposal that briefly describe your project concept and goals in one page by 11/04. You should turn in a write-up (< 10 pages) describing your project and its outcomes, similar to a research-level publication. I suggest the latex styles for [NeurIPS](https://nips.cc/Conferences/2019/PaperInformation/StyleFiles) or [ICLR](https://iclr.cc/Conferences/2019/CallForPapers). There will be in class project presentation at the end of the term. Not presenting your projects will be taken as voluntarily `giving up` the opportunity for the final write-ups.



### Tentative Schedule

| Week  | Date | Topics       |    Notes   |
| ----- |------| -----        |   -----    |
| 1     |09/09 | Introduction |            |
|       |09/11 | Convex Optimization, Gradient Descent, Iterative Reweighted Least Squares|   |
| 2     |09/16 | Advanced Gradient Descent Methods |      |
| 3     |09/23 | Numerical Quadrature, Monte Carlo Methods|  PS1 out, due 10/07
|       |09/25 | Exact Simulation, Variance Reduction Techniques|    |
| 4     |09/30 | -- |   National Day  |
| 5     |10/07 | Markov Chain Monte Carlo |     |
|       |10/09 | Improving Mixing and Convergence, Auxiliary Variable Methods|       <!--PS2 out, due 10/23-->
| 6     |10/14 | Hamiltonian Monte Carlo, Adaptive MCMC|     |
| 7     |10/21 | Scalable MCMC Methods  |       |
|       |10/23 | Expectation Maximization |         |
| 8     |10/28 | Convergence and EM Variants |       <!--PS3 out, due 11/11  -->
| 9     |11/04 | Variational Bayesian EM |        `Proposal Presentation`
|       |11/06 | Variational Inference, Mean Field VI |      |
| 10    |11/11 | Stochastic Variational Inference |      |
| 11    |11/18 | Choice of Training Objectives, Expectation Propagation |        <!-- PS4 out, due 12/02 -->
|       |11/20 | Normalizing Flow, Combinig VI and MCMC |          |
| 12    |11/25 | Autoregressive Models |       |
| 13    |12/02 | Variational Autoencoder  |    |
|       |12/04 | Generative Adversarial Networks |     |
| 14    |12/09 | Applications in Computational Biology |     |
| 15    |12/16 | Project Presentation  |    |
|       |12/18 | Project Presentation  |    |
| 16    |12/23 | Project Presentation  |    |





