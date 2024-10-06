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
      <td><a href="calculus-review-notes.pdf">[Notes]</a></td>
    </tr>
    <tr>
    <td  colspan="3" style="text-align: center"><b>Three Ingredients of Machine Learning; Linear Predictions</b></td>
    </tr>
    <tr>
      <td>Sep 10</td>
      <td> Linear regression and least-squares problem</td>
      <td rowspan="4"  style="vertical-align:middle"><a href="linear-prediction-notes.pdf">[Notes]</a></td>
    </tr>
    <tr>
      <td>Sep 12</td>
      <td>Gradient descent for unconstrained optimization </td>
    </tr>
    <tr>
      <td>Sep 17</td>
      <td>More on gradient descent; review of subspaces and hyperplanes </td>
    </tr>
      <tr>
      <td>Sep 19</td>
      <td>Linear classification: Perceptron, SVM, and logistic regression </td>
    </tr>
        <tr>
    <td  colspan="3" style="text-align: center"><b>Support Vector Machines and Kernel Methods</b></td>
    </tr>
    <tr>
      <td>Sep 24</td>
      <td>Margin-maximization principle and hard-margin SVM</td>
        <td rowspan="6"  style="vertical-align:middle">[Notes]</td>
    </tr>
    <tr>
      <td>Sep 26</td>
      <td>Review of convex analysis; KKT conditions for convex problems </td>
    </tr>
    <tr>
      <td>Oct 01</td>
      <td>Analysis of hard-margin SVMs; soft-margin SVM</td>
    </tr>
    <tr>
      <td>Oct 03</td>
      <td>Property of soft-margin SVMs; solving SVM problem via stochastic gradient descent</td>
    </tr>
    <tr>
      <td>Oct 08</td>
      <td>Kernel methods</td>
    </tr>
    <tr>
      <td>Oct 10</td>
      <td>Beyond binary classification: multiclass and other learning settings</td>
    </tr>
    <tr>
    <td  colspan="3" style="text-align: center"><b>Elements of Statistical Learning Theory</b></td>
    </tr>
    <tr>
    <td>Oct 15</td>
    <td> </td>
    <td rowspan="4" style="vertical-align:middle">[Notes]</td>
    </tr>
    <tr>
    <td>Oct 17</td>
    <td></td>
    </tr>
    <tr>
    <td>Oct 22</td>
    <td> </td>
    </tr>
    <tr>
    <td>Oct 24</td>
    <td> </td>
    </tr>
    <tr>
    <td  colspan="3" style="text-align: center"><b>Ensemble Methods: from Simple to Powerful</b></td>
    </tr>
    <tr>
    <td>Oct 29</td>
    <td> </td>
    <td rowspan="6" style="vertical-align:middle">[Notes]</td>
    </tr>
    <tr>
    <td>Oct 31</td>
    <td> </td>
    </tr>
    <tr>
    <td>Nov 05</td>
    <td> </td>
    </tr>
    <tr>
    <td>Nov 07</td>
    <td> </td>
    </tr>
    <tr>
    <td>Nov 12</td>
    <td> </td>
    </tr>    <tr>
    <td>Nov 14</td>
    <td> </td>
    </tr>
  </tbody>
</table>


<!-- <table rules="groups" class="fixed">
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
[HW1](HW1.pdf)  (Due: Oct 06, 2024)  
[HW2]  (Due: xxx 2024)  
[HW3]  (Due: xxx 2024)  
[HW4]  (Due: xxx 2024)  
[HW5]  (Due: xxx 2024)  
