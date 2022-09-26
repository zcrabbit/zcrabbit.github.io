---
layout: page
title: Statistical Models & Computing Methods, Fall 2022
author: Cheng Zhang
---


### Basic Info
- Instructor: Cheng Zhang (<chengzhang@math.pku.edu.cn>)
- Teaching Assistant: Tianyu Xie (<tianyuxie@pku.edu.cn>)
- Class times: Tuesday 8:00-9:50am, Even Thursday 10:10am-12:00pm, Classroom Building No.3, Room 405  
- Office hours: Thursday 3:00-5:00pm or by appointment, 315 Building No.20
- [Syllabus]({{sites.baseurl}}/courses/Syllabus-smcm-f22.pdf)
  
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
- 09/06/2022: [Lecture 1 - Introduction]({{sites.baseurl}}/static/slides/smcm_fall22/lec01.pdf)
- 09/13/2022: [Lecture 2 - Optimization]({{sites.baseurl}}/static/slides/smcm_fall22/lec02.pdf)   
  Textbook on convex optimization: <https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf> 
- 09/15/2022: [Lecture 3 - Advanced Gradient Methods]({{sites.baseurl}}/static/slides/smcm_fall22/lec03.pdf) 
- 09/20/2022: [Lecture 4 - Numerical Integration]({{sites.baseurl}}/static/slides/smcm_fall22/lec04.pdf)
- 09/27/2021: [Lecture 5 - Advanced Monte Carlo]({{sites.baseurl}}/static/slides/smcm_fall22/lec05.pdf) 

### Assignments
- 09/20/2022: [Homework 1]({{sites.baseurl}}/static/slides/smcm_fall22/hw01.pdf), **Due** `10/04/2022`



### Final Project
You may structure your project exploration around a general problem type, algorithm, or data set, but should explore around your problem, testing thoroughly or comparing to alternatives. You may work on the project as teams. Each team may have 2-3 people. Please form your team by the end the 4th week. You should submit a project proposal that briefly describe your project concept and goals in one page by 10/27. You should turn in a write-up (< 10 pages) describing your project and its outcomes, similar to a research-level publication. I suggest the latex styles for [NeurIPS](https://nips.cc/Conferences/2019/PaperInformation/StyleFiles) or [ICLR](https://iclr.cc/Conferences/2019/CallForPapers). There will be in class project presentation at the end of the term. Not presenting your projects will be taken as voluntarily `giving up` the opportunity for the final write-ups.



### Tentative Schedule

| Week  | Date | Topics       |    Notes   |
| ----- |------| -----        |   -----    |
| 1     |09/06 | Introduction |            |
| 2     |09/13 | Convex Optimization, Gradient Descent, Iterative Reweighted Least Squares|   |
|       |09/15 | Advanced Gradient Descent Methods |      |
| 3     |09/20 | Numerical Quadrature, Monte Carlo Methods|  <!--PS1 out, due 10/14-->
| 4     |09/27 | Exact Simulation, Variance Reduction Techniques|    |
|       |09/29 | Markov Chain Monte Carlo |     |
| 5     |10/04 | Improving Mixing and Convergence, Auxiliary Variable Methods |   |
| 6     |10/11 | Hamiltonian Monte Carlo, Adaptive MCMC|       <!--PS2 out, due 10/23-->
|       |10/13 | Scalable MCMC Methods|     |
| 7     |10/18 | Expectation Maximization |       |
| 8     |10/25 | Convergence and EM Variants |         |
|       |10/27 | Variational Bayesian EM |  `Proposal Presentation`
| 9     |11/01 | Variational Inference, Mean Field VI |        
| 10    |11/08 | Stochastic Variational Inference |      |
|       |11/10 | Choice of Training Objectives, Expectation Propagation, Stein Variational Gradient Descent |      |
| 11    |11/15 | Normalizing Flow, Combinig VI and MCMC |        
| 12    |11/22 | Autoregressive Models |          |
|       |11/24 | Variational Autoencoder |       |
| 13    |11/29 | Generative Adversarial Networks  |    |
| 14    |12/06 | Energy-based Models, Score-based Models |     |
|       |12/08 | Project Presentation  |     |
| 15    |12/13 | Project Presentation  |    |