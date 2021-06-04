---
layout: page
title: Bayesian Theory and Computation, Spring 2021
author: Cheng Zhang
---

### Basic Info
- Instructor: Cheng Zhang (<chengzhang@math.pku.edu.cn>)
- Class times and location: odd Tuesday 1:00-2:50pm, Friday 3:10-5:00pm, Science Classroom Building, Room 407  
- Office hours: Thursday 3:00-5:00pm or by appointment, 1279 Science Building No.1
- [Syllabus]({{sites.baseurl}}/courses/Syllabus-btc-s21.pdf)
  
### Description and Objectives
The objective of this course is to explore Bayesian statistical theories and methods, and discuss their application in real life problems. Students would learn how to formulate a scientific question by constructing a Bayesian model, and perform Bayesian statistical inference to answer that question. Throughout this course, students would be exposed to the theory of Bayesian inference. They would also learn several computational techniques, such as importance sampling, sequential Monte Carlo, Markov Chain Mote Carlo (MCMC) algorithms, variational inference (VI), and use these techniques for Bayesian analysis of real data. Additional topics may vary. Coursework will include computer assignments.

### Prerequisites
Multivariate calculus, linear algebra, graduate level courses in probability and statistics, applied stochastic processes

### Recommended Textbooks
**Main textbook**

- Gelman, A., Carlin, J., Stern, H., and Rubin, D. (2003). Bayesian Data Analysis, 2nd Edition, Chapman & Hall.

Other interesting references

- Liu, J. (2001). Monte Carlo Strategies in Scientific Computing, Springer-Verlag.
- Lange, K. (2002). Numerical Analysis for Statisticians, Springer-Verlag, 2nd Edition.
- Keener, R. W. (2010). Theoretical Statistics: Topics for a Core Course, Springer.
- Christian, P. R. (2004). The Bayesian Choice, Springer.

### Grading
- 4 problem sets (15% each), 60%
- final project (40%): midterm proposal (5%) + oral presentation (10%) + final write-up (25%)

There will be `7` free late days in total, use them in your own ways. Afterwards, late homework will be discounted by 25% for each additional day. Not acceptable after `3` late days per problem set (PS). Late policy `does not apply` to the final project, please submit it on time. Discussing assignments verbally with your classmates is allowed and encouraged. However, you should finish your work independently. Identified cheating incidents will be reported and will result in zero grades.

### Computer and Technical Requirements

We will use python during the course. A good Python tutorial is available at <http://www.scipy-lectures.org/>. You may also find another shorter tutorial useful at <http://cs231n.github.io/python-numpy-tutorial/>. If you have never used Python before, I recommend using Anaconda Python 3.7 <https://www.continuum.io/>.

### Lectures
- 03/09/2021: [Lecture 1 - Introduction]({{sites.baseurl}}/static/slides/btc_spring21/lec01.pdf) 
- 03/12/2021: [Lecture 2 - Single and Multiple Parameter Models]({{sites.baseurl}}/static/slides/btc_spring21/lec02.pdf)
- 03/19/2021: [Lecture 3 - Monte Carlo Methods]({{sites.baseurl}}/static/slides/btc_spring21/lec03.pdf)
- 03/23/2021: [Lecture 4 - Markov Chain Monte Carlo I]({{sites.baseurl}}/static/slides/btc_spring21/lec04.pdf)
- 03/26/2021: [Lecture 5 - Markov Chain Monte Carlo II]({{sites.baseurl}}/static/slides/btc_spring21/lec05.pdf)
- 04/02/2021: [Lecture 6 - Linear and Generalized Linear Models]({{sites.baseurl}}/static/slides/btc_spring21/lec06.pdf)
- 04/06/2021: [Lecture 7 - Decision Theory and Model Selection]({{sites.baseurl}}/static/slides/btc_spring21/lec07.pdf)
- 04/09/2021: [Lecture 8 - Importance Sampling]({{sites.baseurl}}/static/slides/btc_spring21/lec08.pdf)
- 04/16/2021: [Lecture 9 - Sequential Monte Carlo]({{sites.baseurl}}/static/slides/btc_spring21/lec09.pdf)
- 04/20/2021: [Lecture 10 - Advanced MCMC]({{sites.baseurl}}/static/slides/btc_spring21/lec10.pdf)
- 04/23/2021: [Lecture 11 - Scalable MCMC]({{sites.baseurl}}/static/slides/btc_spring21/lec11.pdf)
- 05/04/2021: [Lecture 12 - Expectation Maximization]({{sites.baseurl}}/static/slides/btc_spring21/lec12.pdf)
- 05/07/2021: [Lecture 13 - Variational EM]({{sites.baseurl}}/static/slides/btc_spring21/lec13.pdf)
- 05/14/2021: [Lecture 14 - Variational Inference]({{sites.baseurl}}/static/slides/btc_spring21/lec14.pdf)
- 05/18/2021: [Lecture 15 - Stochastic Variational Inference]({{sites.baseurl}}/static/slides/btc_spring21/lec15.pdf)
- 05/21/2021: [Lecture 16 - Advanced VI]({{sites.baseurl}}/static/slides/btc_spring21/lec16.pdf)
- 05/28/2021: [Lecture 17 - Gaussian Processes]({{sites.baseurl}}/static/slides/btc_spring21/lec17.pdf)
- 06/01/2021: [Lecture 18 - Dirichlet Processes]({{sites.baseurl}}/static/slides/btc_spring21/lec18.pdf)


### Assignments
- 03/26/2021: [Homework 1]({{sites.baseurl}}/static/slides/btc_spring21/hw01.pdf), **Due** `04/09/2021`
- 04/20/2021: [Homework 2]({{sites.baseurl}}/static/slides/btc_spring21/hw02.pdf), **Due** `05/04/2021`
- 05/14/2021: [Homework 3]({{sites.baseurl}}/static/slides/btc_spring21/hw03.pdf), **Due** `05/28/2021`
- 06/04/2021: [Homework 4]({{sites.baseurl}}/static/slides/btc_spring21/hw04.pdf), **Due** `06/18/2021` &nbsp; Data: [p1]({{sites.baseurl}}/static/datasets/btc_hw4_lda_data.p), [p4]({{sites.baseurl}}/static/datasets/btc_hw4_dp_data.npy)


### Final Project
You may structure your project exploration around a general problem type, algorithm, or data set, but should explore around your problem, testing thoroughly or comparing to alternatives. You may work on the project as teams. Each team may have up to `4` people. Please form your team by the end the `4th` week. You should present a project proposal that briefly describe your project concept and goals in one slide at midterm. You should turn in a write-up (< 10 pages) describing your project and its outcomes, similar to a research-level publication. I suggest the latex styles for [NeurIPS](https://nips.cc/Conferences/2019/PaperInformation/StyleFiles) or [ICLR](https://iclr.cc/Conferences/2019/CallForPapers). There will be in class project presentation at the end of the term. Not presenting your projects will be taken as voluntarily `giving up` the opportunity for the final write-ups.



### Tentative Schedule

| Week  | Date | Topics       |    Notes   |
| ----- |------| -----        |   -----    |
| 1     |03/09 | Introduction |            |
|       |03/12 | Single- and Multi- Parameter Models|   |
| 2     |03/19 | Monte Carlo Methods, Markov Processes|      |
| 3     |03/23 | Metropolis Hastings, Gibbs Sampling|  
|       |03/26 | Parallel Tempering, Slice Sampling, Hierarchical Models|    |
| 4     |04/02 | Linear Models, Generalized Linear Models |    |
| 5     |04/06 | Bayesian Decision Theory, Bayesian Model Selection |     |
|       |04/09 | Importance Sampling, Variance Reduction Techniques|       <!--PS2 out, due 10/23-->
| 6     |04/16 | Sequential Monte Carlo|     |
| 7     |04/20 | Hamiltonian Monte Carlo, Adaptive MCMC|       |
|       |04/23 | Scalable MCMC Methods |         |
| 8     |04/30 | -- |    International Workers’ Day |
| 9     |05/04 | Expectation Maximization |     
|       |05/07 | Variational Bayesian EM |   `proposal presentation`   |
| 10    |05/14 | Variational Inference, Mean Field VI |      |
| 11    |05/18 | Stochastic Variational Inference |       
|       |05/21 | Normalizing Flow, Combining VI and MCMC |          |
| 12    |05/28 | Gaussian Processes, Sparse Gaussian Processes|       |
| 13    |06/01 | Dirichlet Processes, DP Mixture Models|    |
|       |06/04 | Project Presentation |     |
| 14    |06/11 | Project Presentation |     |
| 15    |06/15 | Project Presentation |    |
|       |06/18 | Project Presentation |    |