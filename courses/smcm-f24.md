---
layout: page
title: Statistical Models & Computing Methods, Fall 2024
author: Cheng Zhang
---


### Basic Info
- Instructor: Cheng Zhang (<chengzhang@math.pku.edu.cn>)
- Teaching Assistant: Shiyue Zhang (<zhangshiyue@stu.pku.edu.cn>) and Shizhe Kun (<2100010658@stu.pku.edu.cn>)
- Class times: Monday 3:10-5:00pm, Even Wednesday 1:00-2:50pm, Classroom Building No.3, Room 505  
- Office hours: Thursday 3:00-5:00pm or by appointment, 315 Building No.20
- [Syllabus]({{sites.baseurl}}/courses/Syllabus-smcm-f24.pdf)
  
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
- Final project (40%): midterm proposal (5%) + oral presentation (10%) + final write-up (25%)

There will be `7` free late days in total, use them in your own ways. Afterwards, late homework will be discounted by 25% for each additional day. Homeworks submitted after `3` late days will not be accepted. Late policy `does not apply` to the final project, please submit it on time. Discussing assignments verbally with your classmates is allowed and encouraged. However, you should finish your work independently. Identified cheating incidents will be reported and will result in zero grades.

### Computer and Technical Requirements

We will use python during the course. A good Python tutorial is available at <http://www.scipy-lectures.org/>. You may also find another shorter tutorial useful at <http://cs231n.github.io/python-numpy-tutorial/>. If you have never used Python before, I recommend using Anaconda Python 3.7 <https://www.continuum.io/>.

### Lectures
- 09/09/2024: [Lecture 1 - Introduction]({{sites.baseurl}}/static/slides/smcm_fall24/lec01.pdf)


### Assignments



### Final Project
You may structure your project exploration around a general problem type, algorithm, or data set, but should explore around your problem, testing thoroughly or comparing to alternatives. You may work on the project as teams. Each team may have 2-4 people. Please form your team by the end the 4th week. You should present a midterm report on your projects in class by 11/11. You should turn in a write-up (< 10 pages) describing your project and its outcomes, similar to a research-level publication. I suggest the latex styles for [NeurIPS](https://nips.cc/Conferences/2019/PaperInformation/StyleFiles) or [ICLR](https://iclr.cc/Conferences/2019/CallForPapers). There will be in class project presentation at the end of the term. Not presenting your projects will be taken as voluntarily `giving up` the opportunity for the final write-ups.



### Tentative Schedule

| Week  | Date | Topics       |    Notes   |
| ----- |------| -----        |   -----    |
| 1     |09/09 | Introduction |            |
|       |09/14 | Convex Optimization, Gradient Descent, Iterative Reweighted Least Squares|   |
| 2     |09/18 | Advanced Gradient Descent Methods |      |
| 3     |09/23 | Numerical Quadrature, Monte Carlo Methods|  <!--PS1 out, due 10/14-->
| 4     |09/30 | Exact Simulation, Variance Reduction Techniques   |   |
|       |10/02 |  --              | National Day Holiday |
| 5     |10/07 |  --              | National Day Holiday |
| 6     |10/14 | Markov Chain Monte Carlo |     |
|       |10/16 | Improving Mixing and Convergence, Auxiliary Variable Methods |   |
| 7     |10/21 | Hamiltonian Monte Carlo, Adaptive MCMC|       <!--PS2 out, due 10/23-->
| 8     |10/28 | Scalable MCMC Methods|     |
|       |10/30 | Expectation Maximization |       |
| 9     |11/04 | Convergence and EM Variants |         |
| 10    |11/11 | Variational Bayesian EM |  `Proposal Presentation`
|       |11/13 | Variational Inference, Mean Field VI |        
| 11    |11/18 | Stochastic Variational Inference |      |
| 12    |11/25 | Choice of Training Objectives, Expectation Propagation, Stein Variational Gradient Descent |      |
|       |11/27 | Normalizing Flow, Combinig VI and MCMC |        
| 13    |12/02 | Autoregressive Models |          |
| 14    |12/09 | Variational Autoencoder, Generative Adversarial Networks  |       |
|       |12/11 | Project Presentation  |    |
| 15    |12/16 | Project Presentation  |     |
| 16    |12/23 | Project Presentation  |     |
|       |12/25 | Project Presentation  |    |