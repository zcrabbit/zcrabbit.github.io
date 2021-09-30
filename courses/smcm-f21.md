---
layout: page
title: Statistical Models & Computing Methods, Fall 2021
author: Cheng Zhang
---


### Basic Info
- Instructor: Cheng Zhang (<chengzhang@math.pku.edu.cn>)
- Teaching Assistant: Tianyu Xie (<tianyuxie@pku.edu.cn>)
- Class times: Even Monday 1:00-2:50pm, Thursday 10:10am-12:00pm, Classroom Building No.3, Room 406  
- Office hours: Thursday 3:00-5:00pm or by appointment, 315 Building No.20
- [Syllabus]({{sites.baseurl}}/courses/Syllabus-smcm-f21.pdf)
  
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
- 09/16/2021: [Lecture 1 - Introduction]({{sites.baseurl}}/static/slides/smcm_fall21/lec01.pdf)  
- 09/20/2019: [Lecture 2 - Optimization]({{sites.baseurl}}/static/slides/smcm_fall21/lec02.pdf)  
  Textbook on convex optimization: <https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf>  
- 09/23/2019: [Lecture 3 - Advanced Gradient Methods]({{sites.baseurl}}/static/slides/smcm_fall21/lec03.pdf)  
- 09/30/2019: [Lecture 4 - Numerical Integration]({{sites.baseurl}}/static/slides/smcm_fall21/lec04.pdf)

### Assignments
- 09/30/2019: [Homework 1]({{sites.baseurl}}/static/slides/smcm_fall21/hw01.pdf), **Due** `10/14/2021`  


### Final Project
You may structure your project exploration around a general problem type, algorithm, or data set, but should explore around your problem, testing thoroughly or comparing to alternatives. You may work on the project as teams. Each team may have 2-3 people. Please form your team by the end the 4th week. You should submit a project proposal that briefly describe your project concept and goals in one page by 11/15. You should turn in a write-up (< 10 pages) describing your project and its outcomes, similar to a research-level publication. I suggest the latex styles for [NeurIPS](https://nips.cc/Conferences/2019/PaperInformation/StyleFiles) or [ICLR](https://iclr.cc/Conferences/2019/CallForPapers). There will be in class project presentation at the end of the term. Not presenting your projects will be taken as voluntarily `giving up` the opportunity for the final write-ups.



### Tentative Schedule

| Week  | Date | Topics       |    Notes   |
| ----- |------| -----        |   -----    |
| 1     |09/16 | Introduction |            |
| 2     |09/20 | Convex Optimization, Gradient Descent, Iterative Reweighted Least Squares|   |
|       |09/23 | Advanced Gradient Descent Methods |      |
| 3     |09/30 | Numerical Quadrature, Monte Carlo Methods|  PS1 out, due 10/14
| 4     |10/04 | -- |  National Day Holiday 
|       |10/07 | -- |  National Day Holiday
| 5     |10/14 | Exact Simulation, Variance Reduction Techniques|    |
| 6     |10/18 | Markov Chain Monte Carlo |     |
|       |10/21 | Improving Mixing and Convergence, Auxiliary Variable Methods|       <!--PS2 out, due 10/23-->
| 7     |10/28 | Hamiltonian Monte Carlo, Adaptive MCMC|     |
| 8     |11/01 | Scalable MCMC Methods  |       |
|       |11/04 | Expectation Maximization |         |
| 9     |11/11 | Convergence and EM Variants |       <!--PS3 out, due 11/11  -->
| 10    |11/15 | Variational Bayesian EM |        `Proposal Presentation`
|       |11/18 | Variational Inference, Mean Field VI |      |
| 11    |11/25 | Stochastic Variational Inference |      |
| 12    |11/29 | Choice of Training Objectives, Expectation Propagation |        <!-- PS4 out, due 12/02 -->
|       |12/02 | Normalizing Flow, Combinig VI and MCMC |          |
| 13    |12/09 | Autoregressive Models |       |
| 14    |12/13 | Variational Autoencoder  |    |
|       |12/16 | Generative Adversarial Networks |     |
| 15    |12/23 | Applications in Computational Biology |     |
| 16    |12/27 | Project Presentation  |    |
|       |12/30 | Project Presentation  |    |