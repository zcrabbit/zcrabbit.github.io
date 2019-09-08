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

There will be `7` free late days in total, use them in your own ways. Afterwards, late homework will be discounted by 25% for each additional day. Not accepted after `3` late days per problem set (PS). Late policy `does not apply` to the final project, please submit it on time. Discussing assignments verbally with classmates is allowed and encouraged. However, you should finish your work independently. Identified cheating incidents will be reported and will result in zero grades.

### Computer and Technical Requirements

We will use python during the course. A good Python tutorial is available at <http://www.scipy-lectures.org/>. You may also find another shorter tutorial useful at <http://cs231n.github.io/python-numpy-tutorial/>. If you have never used Python before, I recommend using Anaconda Python 3.7 <https://www.continuum.io/>.

### Lectures
- 09/09/2019: [Lecture 1 - Introduction]({{sites.baseurl}}/static/slides/mcs_fall19/lec01.pdf)

### Assignments

### Final Project
You may structure your project exploration around a general problem type, algorithm, or data set, but should explore around your problem, testing thoroughly or comparing to alternatives. You may work on the project as teams. Each team may have 2-3 people. Please form you team by the end the 4th week. You should submit a project proposal that briefly describe your project concept and goals in one page by 11/04. You should turn in a write-up (< 10 pages) describing your project and its outcomes, similar to a research-level publication. I suggest the latex styles for [NeurIPS](https://nips.cc/Conferences/2019/PaperInformation/StyleFiles) or [ICLR](https://iclr.cc/Conferences/2019/CallForPapers). There will be in class project presentation at the end of the term. Not presenting your projects will be taken as voluntarily `giving up` the opportunity for the final write-ups.



### Tentative Schedule

| Week  | Date | Topics       |    Notes   |
| ----- |------| -----        |   -----    |
| 1     |09/09 | Introduction |            |
|       |09/11 | Convex Optimization, Gradient Descent, Iterative Reweighted Least Squares|   |
| 2     |09/16 | Advanced Gradient Descent Methods |      <!--PS1 out, due 09/25-->
| 3     |09/23 | Numerical Quadrature, Monte Carlo Methods|   |
|       |09/25 | Exact Simulation, Variance Reduction Techniques|    |
| 4     |09/30 | -- |   National Day  |
| 5     |10/07 | Metropolis-Hastings, Gibbs Sampling, Slice Sampling |     |
|       |10/09 | Improving Mixing and Convergence, Tempering, Adaptive MCMC|       <!--PS2 out, due 10/23-->
| 6     |10/14 | Hamiltonian Monte Carlo |     |
| 7     |10/21 | Scalable MCMC Methods  |       |
|       |10/23 | Expectation Maximization |         |
| 8     |10/28 | EM Variants |       <!--PS3 out, due 11/11  -->
| 9     |11/04 | Variational Bayesian EM |        Proposal deadline
|       |11/06 | Variational Inference, Mean Field VI |      |
| 10    |11/11 | Stochastic Variational Inference |      |
| 11    |11/18 | Choice of Training Objectives, Advanced VI |        <!-- PS4 out, due 12/02 -->
|       |11/20 | Combinig VI and MCMC |          |
| 12    |11/25 | Variational Autoencoder  |       |
| 13    |12/02 | Generative Adversarial Networks |    |
|       |12/04 | Adversarial Variational Bayes, Flow Based Generative Models  |     |
| 14    |12/09 | Applications in Computational Biology |     |
| 15    |12/16 | Project Presentation  |    |
|       |12/18 | Project Presentation  |    |
| 16    |12/23 | Project Presentation  |    |




