---
layout: page
title: Bayesian Theory and Computation, Spring 2024
author: Cheng Zhang
---

### Basic Info
- Instructor: Cheng Zhang (<chengzhang@math.pku.edu.cn>)
- Teaching Assistant: Longlin Yu (<llyu@pku.edu.cn>) and Shiyue Zhang (<zhangshiyue@stu.pku.edu.cn>)
- Class times and location: Monday 10:10-12:00pm, odd Wednesday 3:10-5:00pm, Classroom Building No.3, Room 106 
- Office hours: Thursday 3:00-5:00pm or by appointment, 315 Building No.20
- [Syllabus]({{sites.baseurl}}/courses/Syllabus-btc-s24.pdf)
  
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
- 02/19/2024: [Lecture 1 - Introduction]({{sites.baseurl}}/static/slides/btc_spring24/lec01.pdf)  
- 02/21/2024: [Lecture 2 - Single and Multiple Parameter Models]({{sites.baseurl}}/static/slides/btc_spring24/lec02.pdf)  
- 02/26/2024: [Lecture 3 - Monte Carlo Methods]({{sites.baseurl}}/static/slides/btc_spring24/lec03.pdf)  
- 03/04/2024: [Lecture 4 - Markov Chain Monte Carlo I]({{sites.baseurl}}/static/slides/btc_spring24/lec04.pdf)  
- 03/06/2024: [Lecture 5 - Markov Chain Monte Carlo II]({{sites.baseurl}}/static/slides/btc_spring24/lec05.pdf)



### Assignments
- 03/06/2024: [Homework 1]({{sites.baseurl}}/static/slides/btc_spring24/hw01.pdf), **Due** `03/20/2024`



### Final Project
You may structure your project exploration around a general problem type, algorithm, or data set, but should explore around your problem, testing thoroughly or comparing to alternatives. You may work on the project as teams. Each team may have up to `3` people. Please form your team by the end the `4th` week. You should present a project proposal that briefly describe your project concept and goals in one slide at midterm. You should turn in a write-up (< 10 pages) describing your project and its outcomes, similar to a research-level publication. I suggest the latex styles for [NeurIPS](https://nips.cc/Conferences/2019/PaperInformation/StyleFiles) or [ICLR](https://iclr.cc/Conferences/2019/CallForPapers). There will be in class project presentation at the end of the term. Not presenting your projects will be taken as voluntarily `giving up` the opportunity for the final write-ups.



### Tentative Schedule

| Week  | Date | Topics       |    Notes   |
| ----- |------| -----        |   -----    |
| 1     |02/19 | Introduction |            |
|       |02/21 | Single- and Multi- Parameter Models|   |
| 2     |02/26 | Monte Carlo Methods, Markov Processes|      |
| 3     |03/04 | Metropolis Hastings, Gibbs Sampling|  
|       |03/06 | Parallel Tempering, Slice Sampling, Hierarchical Models|    |
| 4     |03/11 | Linear Models, Generalized Linear Models |    |
| 5     |03/18 | Bayesian Decision Theory, Bayesian Model Selection |     |
|       |03/20 | Importance Sampling, Variance Reduction Techniques|       |
| 6     |03/25 | Sequential Monte Carlo|     |
| 7     |04/01 | MALA, Hamiltonian Monte Carlo, Adaptive MCMC|       |
|       |04/03 | Scalable MCMC Methods |         |
| 8     |04/08 | Convergence Theory of MCMC |         |
| 9     |04/15 | Expectation Maximization |           |
|       |04/17 | Variational Bayesian EM |   `proposal presentation`   |
| 10    |04/22 | Variational Inference, Mean Field VI |                |
| 11    |04/29 | --          | Labour Day |
|       |05/01 | --          | Labour Day |
| 12    |05/06 | Stochastic Variational Inference |         |
| 13    |05/13 | Gaussian Processes, Sparse Gaussian Processes |       |
|       |05/15 | Dirichlet Processes, DP Mixture Models |      |
| 14    |05/20 | Project Presentation |              |
| 15    |05/27 | Project Presentation |    |
|       |05/29 | Project Presentation |   |
| 16    |06/03 | Project Presentation |    |