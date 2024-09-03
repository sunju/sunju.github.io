---
layout: page
permalink: /teach/ML-Fall-2024/
title: Advanced Machine Learning
---

What are the state-of-the-art machine learning methods and why do they work? This graduate-level introductory course to machine learning focuses on the foundations of modern machine learning. We will cover selected topics from supervised learning, unsupervised learning, generative learning, and interactive learning. For each topic, we will describe key algorithmic ideas/intuitions and basic theoretical insights. By the end of the course, students will master main machine learning techniques, and apply/optimize/develop them for specific applications. 


**Syllabus**: [Syllabus](CSCI5525_2024_Fall.pdf)

**Who**: [Professor Ju Sun](https://sunju.org/) (Instructor)   Email: jusun AT umn.edu   (Office Hours: 4--6pm Thur) <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Leon Luo](https://gaoxiangluo.github.io/)  Email: luo00042 AT umn.edu   (Office Hours: 3--4pm Mon) 
 
**When/Where**: Tue/Thur 2:30 -- 3:45pm @ Mechanical Engineering 108 (in-person only with UNITE option)

**Lecture Schedule**

<table rules="groups" class="fixed">
    <col width="15%" />
   <col width="75%" />
   <col width="10%" />
  <thead>
    <tr>
      <th style="text-align: left">Date</th>
      <th style="text-align: center">Topics</th>
      <th style="text-align: center">Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Sep 03</td>
      <td>Overview</td>
      <td><a href="https://docs.google.com/presentation/d/1DHWL5TFlDDjd1yE8sHRkuGXjXbrqjH2UBTZkVNAamjk/edit?usp=sharing">[Slides]</a></td>
    </tr>
    <tr>
      <td>Sep 05</td>
      <td>Review of high-dimensional calculus</td>
      <td>[Notes]</td>
    </tr>
    <tr>
    <td  colspan="3" style="text-align: center"><b>Linear Predictions</b></td>
    </tr>
    <tr>
      <td>Sep 10</td>
      <td> Linear regression and least-squares problem</td>
      <td rowspan="3"  style="vertical-align:middle">[Notes]</td>
    </tr>
    <tr>
      <td>Sep 12</td>
      <td>Gradient descent for unconstrained optimization </td>
    </tr>
    <tr>
      <td>Sep 17</td>
      <td>Linear classification: Perceptron, SVM, and logistic regression </td>
    </tr>
  </tbody>
</table>

<!-- <table rules="groups" class="fixed">
    <col width="15%" />
   <col width="75%" />
   <col width="10%" />
  <thead>
    <tr>
      <th style="text-align: left">Date</th>
      <th style="text-align: center">Topics</th>
      <th style="text-align: center">Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Jan 20</td>
      <td>Overview</td>
      <td><a href="lecture_intro.pdf">[Slides]</a></td>
    </tr>
    <tr>
    <td  colspan="3" style="text-align: center"><b>Calculus Review</b></td>
    </tr>
    <tr>
      <td>Jan 25</td>
      <td>Review of high-dimensional calculus - I</td>
      <td rowspan="2"  style="vertical-align:middle"><a href="calculus_review.pdf">[Notes]</a></td>
    </tr>
    <tr>
      <td>Jan 27</td>
      <td>Review of high-dimensional calculus - II</td>
    </tr>
    <tr>
    <td  colspan="3" style="text-align: center"><b>Linear Predictions</b></td>
    </tr>
    <tr>
      <td>Feb 01</td>
      <td> Linear regression and least-squares problem</td>
      <td rowspan="3"  style="vertical-align:middle"><a href="linear_predictions.pdf">[Notes]</a></td>
    </tr>
    <tr>
      <td>Feb 03</td>
      <td>Gradient descent for unconstrained optimization </td>
    </tr>
    <tr>
      <td>Feb 15</td>
      <td>Linear classification: Perceptron, SVM, and logistic regression </td>
    </tr>
    <tr>
    <td  colspan="3" style="text-align: center"><b>Support Vector Machines and Kernel Methods</b></td>
    </tr>
    <tr>
      <td>Feb 17</td>
      <td>Subspaces, hyperplanes, and margins  </td>
        <td rowspan="5"  style="vertical-align:middle">[Notes]</td>
    </tr>
    <tr>
      <td>Feb 22</td>
      <td>Hard-margin SVMs and properties </td>
    </tr>
    <tr>
      <td>Feb 24</td>
      <td>Review of convex analysis & optimization; analysis of hard-margin SVMs  </td>
    </tr>
    <tr>
      <td>Mar 01</td>
      <td>Soft-margin SVMs; optimizing SVMs  </td>
    </tr>
    <tr>
      <td>Mar 03</td>
      <td>Kernel methods</td>
    </tr>
    <tr>
    <td  colspan="3" style="text-align: center"><b>Elements of Statistical Learning Theory</b></td>
    </tr>
    <tr>
    <td>Mar 08</td>
    <td>PAC learning with finite hypothesis classes </td>
    <td rowspan="4" style="vertical-align:middle">[Notes]</td>
    </tr>
    <tr>
    <td>Mar 10</td>
    <td>Agnostic PAC learning with finite hypothesis classes; Uniform convergence </td>
    </tr>
    <tr>
    <td>Mar 15</td>
    <td>Agnostic PCA learning with infinite hypothesis classes; Rademacher complexity </td>
    </tr>
    <tr>
    <td>Mar 17</td>
    <td>VC dimensions; Bias-complexity tradeoff and model selection </td>
    </tr>
    <tr>
    <td  colspan="3" style="text-align: center"><b>Ensemble Methods: from Simple to Powerful</b></td>
    </tr>
    <tr>
    <td>Mar 22</td>
    <td> Decision stumps and their linear combinations</td>
    <td rowspan="6" style="vertical-align:middle">[Notes]</td>
    </tr>
    <tr>
    <td>Mar 24</td>
    <td> Adaboost and its training error</td>
    </tr>
    <tr>
    <td>Mar 29</td>
    <td>Generalizations of Adaboost: greedy methods and gradient methods</td>
    </tr>
    <tr>
    <td>Mar 31</td>
    <td>Computing with decision trees</td>
    </tr>
    <tr>
    <td>Apr 12</td>
    <td>CART; Generalization gap of Adaboost </td>
    </tr>
    <tr>
    <td>Apr 14</td>
    <td> Bagging and random forests </td>
    </tr>
    <td  colspan="3" style="text-align: center"><b>Linear and Nonlinear Dimension Reduction</b></td>
    <tr>
    <td>Apr 19</td>
    <td>PCA as subspace fitting/autoencoder; random projection </td>
    <td rowspan="2" style="vertical-align:middle">[Notes]</td>
    </tr>
    <tr>
    <td>Apr 21</td>
    <td>Compressive sensing; nonlinear dimension reduction</td>
    </tr>
      <td  colspan="3" style="text-align: center"><b>Clustering</b></td>
    <tr>
    <td>Apr 26</td>
    <td>K-means, hierarchical clustering, spectral clustering </td>
      <td rowspan="2" style="vertical-align:middle">[Notes]</td>
    </tr>
    <tr>
    <td>Apr 28</td>
    <td> More on spectral clustering; mode seeking methods</td>
    </tr>
    <td  colspan="3" style="text-align: center"><b>Generative Models</b></td>
    <tr>
    <td>May 03</td>
    <td> Mixture modeling, MLE, and EM principle</td>
    <td rowspan="2" style="vertical-align:middle">[Notes]</td>
    </tr>
    <tr>
    <td>May 05</td>
    <td>MAP, normalization flows, GANs </td>
    </tr>
    <tr>
    <td  colspan="3" style="text-align: center"><b>Neural Networks: Taking the Universal Power</b></td>
    </tr>
    <tr>
    <td>Apr 05</td>
    <td> </td>
      <td rowspan="2" style="vertical-align:middle">[Notes]</td>
    </tr>
    <tr>
    <td>Apr 07</td>
    <td> </td>
    </tr>
  </tbody>
</table> -->

**Homework Assignments**  
[HW1]  (Due: xxx 2024)  
[HW2]  (Due: xxx 2024)  
[HW3]  (Due: xxx 2024)  
[HW4]  (Due: xxx 2024)  
[HW5]  (Due: xxx 2024)  
