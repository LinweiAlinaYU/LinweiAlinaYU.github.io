---
title: "The Meaning of ‘Experiment’ in the Chemistry Curriculum Standards in China: A Content Analysis"
excerpt: "This is the project I am currently working on. <br/><img src='/images/ZNN-1.png' style='width: 90%;'>"
collection: research
---

It is popular approach to employ zeroing neural networks (ZNN) to handle time-varying problems. However, most of the existing methods have limited flexibility in the discretization process, which seriously affects the final effect of the model. To solve this problem, in this paper, we present **a new discrete-time ZNN (DTZNN) for handling discrete time-varying minimization problem**. In detail, the new DTZNN is proposed with four-instant general discretization formula, which has a adjustable parameter $d$. Generally speaking, in the process of discretization, different values of $d$ and time interval can influence the residual error observably. In order to verify the effectiveness of our method, we conduct multiple numerical experiments. The numerical experiment results show that the new DTZNN has effectiveness and superiority for handling discrete time-varying minimization problem.

**Zeroing neural network** is a special case of neural network with this structure, which has the structural characteristics of RNN and also has some independent designs. It is used to solve the minimization problem of time-varying signal.  
<br/><img src='/images/ZNN-2.png' style='width: 100%;'>

In this paper, to further optimize and add more flexibility to the related DTZNN, we present **the general four-instant discretization formula**, which has an adjustable parameter $d$, for the discretizations process.  
<br/><img src='/images/ZNN-3.png' style='width: 100%;'>

We designed two experimental functions to test the performance of the new DTZNN. The experimental results have demonstrated that our designed ZNN exhibits superior performance and enhanced flexibility.  
<br/><img src='/images/ZNN-4.png' style='width: 100%;'>

 We have also summarized the variations in residual error and their relationship with $d$:

+ When $d$ is not taken as 1, the error decreases faster than when $d$ is taken as 1.  

+ When $d$ is negative, error decreases faster than when $d$ is positive.

+ When is positive, the error drops more quickly the higher the absolute value of $d$.  
+ When is negative, the error drops more quickly the smaller the absolute value of $d$.
