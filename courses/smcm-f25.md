---
layout: page
title: Statistical Models & Computing Methods, Fall 2025
author: Cheng Zhang
---


### Basic Info
- Instructor: Cheng Zhang (<chengzhang@math.pku.edu.cn>)
- Teaching Assistant: Shiyue Zhang (<zhangshiyue@stu.pku.edu.cn>) and Longlin Yu (<llyu@pku.edu.cn>) 
- Class times: Monday 3:10-5:00pm, Even Wednesday 10:10-12:00pm, Classroom Building No.3, Room 107  
- Office hours: Thursday 3:00-5:00pm or by appointment, 315 Building No.20
- [Syllabus]({{sites.baseurl}}/courses/Syllabus-smcm-f25.pdf)
  
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
- 09/08/2025: [Lecture 1 - Introduction]({{sites.baseurl}}/static/slides/smcm_fall25/lec01.pdf)  
- 09/15/2025: [Lecture 2 - Optimization]({{sites.baseurl}}/static/slides/smcm_fall25/lec02.pdf)  
  Textbook on convex optimization: <https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf> 
- 09/17/2025: [Lecture 3 - Advanced Gradient Methods]({{sites.baseurl}}/static/slides/smcm_fall25/lec03.pdf)  
- 09/22/2025: [Lecture 4 - Numerical Integration]({{sites.baseurl}}/static/slides/smcm_fall25/lec04.pdf)  
- 09/29/2025: [Lecture 5 - Advanced Monte Carlo]({{sites.baseurl}}/static/slides/smcm_fall25/lec05.pdf)  


### Assignments
- 09/22/2025: [Homework 1]({{sites.baseurl}}/static/slides/smcm_fall25/hw01.pdf), **Due** `10/13/2025` 



### Final Project
You may structure your project exploration around a general problem type, algorithm, or data set, but should explore around your problem, testing thoroughly or comparing to alternatives. You may work on the project as teams. Each team may have 2-4 people. Please form your team by the end the 4th week. You should present a midterm report on your projects in class by 11/10. You should turn in a write-up (< 10 pages) describing your project and its outcomes, similar to a research-level publication. I suggest the latex styles for [NeurIPS](https://nips.cc/Conferences/2019/PaperInformation/StyleFiles) or [ICLR](https://iclr.cc/Conferences/2019/CallForPapers). There will be in class project presentation at the end of the term. Not presenting your projects will be taken as voluntarily `giving up` the opportunity for the final write-ups.



### Tentative Schedule

| Week  | Date | Topics       |    Notes   |
| ----- |------| -----        |   -----    |
| 1     |09/08 | Introduction |            |
| 2     |09/15 | Convex Optimization, Gradient Descent, Iterative Reweighted Least Squares|   |
|       |09/17 | Advanced Gradient Descent Methods |      |
| 3     |09/22 | Numerical Quadrature, Monte Carlo Methods|  <!--PS1 out, due 10/14-->
| 4     |09/29 | Exact Simulation, Variance Reduction Techniques   |   |
|       |10/01 |  --              | National Day Holiday |
| 5     |10/06 |  --              | National Day Holiday |
| 6     |10/13 | Markov Chain Monte Carlo |     |
|       |10/15 | Improving Mixing and Convergence, Auxiliary Variable Methods |   |
| 7     |10/20 | Hamiltonian Monte Carlo, Adaptive MCMC|       <!--PS2 out, due 10/23-->
| 8     |10/27 | Scalable MCMC Methods|     |
|       |10/29 | Expectation Maximization |       |
| 9     |11/03 | Convergence and EM Variants |         |
| 10    |11/10 | Variational Bayesian EM |  `Proposal Presentation`
|       |11/12 | Variational Inference, Mean Field VI |        
| 11    |11/17 | Stochastic Variational Inference |      |
| 12    |11/24 | Choice of Training Objectives, Expectation Propagation, Stein Variational Gradient Descent |      |
|       |11/26 | Normalizing Flow, Combinig VI and MCMC |        
| 13    |12/01 | Autoregressive Models |          |
| 14    |12/08 | Variational Autoencoder, Generative Adversarial Networks  |       |
|       |12/10 | Project Presentation  |    |
| 15    |12/15 | Project Presentation  |     |
| 16    |12/22 | Project Presentation  |     |
|       |12/24 | Project Presentation  |    |