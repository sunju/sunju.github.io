---
layout: page
permalink: /research/dict-learn/
title: Dictionary Learning, Blind Deconvolution, Deep Learning
---
Learning dictionaries/atomic sets that induce structured representation on data. Applications are still explosively emerging, especially of deep learning, where one allows multi-level nonlinear cascading of representation. Hence formulations to the problems are fairly diverse. We will roughly organize the references according to the problem they try to solve, concentrated on recent literature of theoretical nature.  (**Update: Sep 28 2018**)

\[<span style="color:red">**S**</span>\] indicates my contribution. 

## Theory 

### $\mathbf{Y} = \mathbf{A} \mathbf{X}$, $\mathbf{A}$ Square, Invertible, Global Recovery 
This problem can be reduced to a sequence of problems, each taking the form of finding sparsest vector in a linear subspace. See also [Structured Element Pursuit](/research/struct-elem/). 

 +  [Efficient Dictionary Learning with Gradient Descent](https://arxiv.org/abs/1809.10313) (2018)
 +  [Fast and robust tensor decomposition with applications to dictionary learning](https://arxiv.org/abs/1706.08672) (2017)
 +  [An improved analysis of the ER-SpUD dictionary learning algorithm](https://arxiv.org/abs/1602.05719) (2016)
 +  [A note on the sample complexity of the Er-SpUD algorithm by Spielman, Wang and Wright for exact recovery of sparsely used dictionaries](https://arxiv.org/abs/1601.02049) (2016)
 +  [Dictionary Learning with Few Samples and Matrix Concentration](https://arxiv.org/abs/1503.08854) (2015)
 +  [Complete Dictionary Recovery over the Sphere](http://arxiv.org/abs/1504.06785) (\[<span style="color:red">**S**</span>\], 2015)  
 +  [Dictionary Learning and Tensor Decomposition via the Sum-of-Squares Method](http://arxiv.org/abs/1407.1543) (2014)
 +  [Sum-of-squares proofs and the quest toward optimal algorithms](http://arxiv.org/abs/1404.5236) (2014)
 +  [Rounding Sum-of-Squares Relaxations](http://arxiv.org/abs/1312.6652) (2013)
 +  [Scaling law for recovering the sparsest element in a subspace](http://math.mit.edu/icg/papers/sparsest-element.pdf) (2013)
 +  [Exact Recovery of Sparsely-Used Dictionaries](http://arxiv.org/abs/1206.5882) (2012)
 
### $\mathbf{Y} = \mathbf{A} \mathbf{X}$, $\mathbf{A}$ Overcomplete, Incoherent, Global Recovery 
 +  [Towards Learning Sparsely Used Dictionaries with Arbitrary Supports](https://arxiv.org/abs/1804.08603) (2018)
 +  [A Provable Approach for Double-Sparse Coding](https://arxiv.org/abs/1711.03638) (2017)
 +  [Alternating minimization for dictionary learning with random initialization](https://arxiv.org/abs/1711.03634) (2017)
 +  [Polynomial-time Tensor Decompositions with Sum-of-Squares](https://arxiv.org/abs/1610.01980) (2016)
 +  [Simple, Efficient, and Neural Algorithms for Sparse Coding](http://arxiv.org/abs/1503.00778) (2015)
 +  [Dictionary Learning and Tensor Decomposition via the Sum-of-Squares Method](http://arxiv.org/abs/1407.1543) (2014)
 +  [Sum-of-squares proofs and the quest toward optimal algorithms](http://arxiv.org/abs/1404.5236) (2014)
 +  [Rounding Sum-of-Squares Relaxations](http://arxiv.org/abs/1312.6652) (2013)
 +  [More Algorithms for Provable Dictionary Learning](http://arxiv.org/abs/1401.0579) (2014)
 +  [Exact Recovery of Sparsely Used Overcomplete Dictionaries](http://arxiv.org/abs/1309.1952) (2013)
 +  [New Algorithms for Learning Incoherent and Overcomplete Dictionaries](http://arxiv.org/abs/1308.6273) (2013)
 +  [Learning Sparsely Used Overcomplete Dictionaries via Alternating Minimization](http://arxiv.org/abs/1310.7991) (2013)
 
### $\mathbf{Y} = \mathbf{A} \mathbf{X}$ Local Correctness
 +  [On the Local Correctness of $\ell^1$ Minimization for Dictionary Learning](http://www.columbia.edu/~jw2966/Geng11-IT.pdf) (2011, $\mathbf{A}$ general)
 +  [Dictionary Identification - Sparse Matrix-Factorisation via $\ell^1$-Minimisation](http://arxiv.org/abs/0904.4774) (2009, $\mathbf{A}$ square)
  
### Single-Kernel Convolutional (aka Blind Deconvolution): $\mathbf{y} = \mathbf{a} \otimes \mathbf{x}$ 
 +  [Structured Local Optima in Sparse Blind Deconvolution](https://arxiv.org/abs/1806.00338) (2018)
 +  [On the Global Geometry of Sphere-Constrained Sparse Blind Deconvolution](http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhang_On_the_Global_CVPR_2017_paper.pdf) (2017)
 +  [Blind Deconvolution by a Steepest Descent Algorithm on a Quotient Manifold](https://arxiv.org/abs/1710.03309) (2017)
 +  [From Blind deconvolution to Blind Super-Resolution through convex programming](https://arxiv.org/abs/1709.09279) (2017)
 +  [BranchHull: Convex bilinear inversion from the entrywise product of signals with known signs](https://arxiv.org/abs/1702.04342) (2017)
 +  [Self-Calibration via Linear Least Squares](https://arxiv.org/abs/1611.04196) (2016)
 +  [Through the Haze: A Non-Convex Approach to Blind Calibration for Linear Random Sensing Models](https://arxiv.org/abs/1610.09028) (2016)
 +  [Fast and guaranteed blind multichannel deconvolution under a bilinear system model](https://arxiv.org/abs/1610.06469) (2016)
 +  [Leveraging Diversity and Sparsity in Blind Deconvolution](https://arxiv.org/abs/1610.06098) (2016)
 +  [Rapid, Robust, and Reliable Blind Deconvolution via Nonconvex Optimization](http://arxiv.org/abs/1606.04933) (2016)
 +  [A Non-Convex Blind Calibration Method for Randomised Sensing Strategies](http://arxiv.org/abs/1605.02615) (2016)
 +  [Empirical Chaos Processes and Blind Deconvolution](https://arxiv.org/abs/1608.08370) (2016)
 +  [Optimal Injectivity Conditions for Bilinear Inverse Problems with Applications to Identifiability of Deconvolution Problems](https://arxiv.org/abs/1603.07316) (2016)
 +  [RIP-like Properties in Subsampled Blind Deconvolution](http://arxiv.org/abs/1511.06146) (2015)
 +  [Blind Recovery of Sparse Signals from Subsampled Convolution](http://arxiv.org/abs/1511.06149) (2015)
 +  [Identifiability and Stability in Blind Deconvolution under Minimal Assumptions](https://arxiv.org/abs/1507.01308) (2015)
 +  [Identifiability in Blind Deconvolution with Subspace or Sparsity Constraints](https://arxiv.org/abs/1505.03399) (2015)
 +  [A Unified Framework for Identifiability Analysis in Bilinear Inverse Problems with Applications to Subspace and Sparsity Models](https://arxiv.org/abs/1501.06120) (2015)
 +  [Fundamental Limits of Blind Deconvolution Part II: Sparsity-Ambiguity Trade-offs](https://arxiv.org/abs/1503.03184) (2015)
 +  [Self-Calibration and Biconvex Compressive Sensing](https://arxiv.org/abs/1501.06864) (2015)
 +  [Fundamental Limits of Blind Deconvolution Part I: Ambiguity Kernel](https://arxiv.org/abs/1411.3810) (2014)
 +  [Sparse blind deconvolution: What cannot be done](https://dx.doi.org/10.1109/ISIT.2014.6875385) (2014)
 +  [Identifiability Scaling Laws in Bilinear Inverse Problems](https://arxiv.org/abs/1402.2637) (2014)
 +  [Near Optimal Compressed Sensing of Sparse Rank-One Matrices via Sparse Power Factorization](http://arxiv.org/abs/1312.0525) (2013)
 +  [Blind Deconvolution using Convex Programming](https://arxiv.org/abs/1211.5608) (2012)

 
### Multi-Kernel Convolutional: $\mathbf{Y} = \sum_i \mathbf{a}_i \otimes \mathbf{x}_i$ 
 +  [On the Reconstruction Risk of Convolutional Sparse Dictionary Learning](https://arxiv.org/abs/1708.08587) (2017)
 +  [Working Locally Thinking Globally: Theoretical Guarantees for Convolutional Sparse Coding](https://arxiv.org/abs/1707.06066) (2017)
 +  [Blind Demixing and Deconvolution at Near-Optimal Rate](https://arxiv.org/abs/1704.04178) (2017)
 +  [Regularized Gradient Descent: A Nonconvex Recipe for Fast Joint Blind Deconvolution and Demixing](https://arxiv.org/abs/1703.08642) (2017) 
 +  [Blind Deconvolution Meets Blind Demixing: Algorithms and Performance Bounds](https://arxiv.org/abs/1512.07730) (2015)
 
### Wavelet/General Scattering Network 
 +  [Lipschitz Properties for Deep Convolutional Networks](https://arxiv.org/abs/1701.05217) (2017)
 +  [Discrete Deep Feature Extraction: A Theory and New Architectures](https://arxiv.org/abs/1605.08283) (2016)
 +  [A Mathematical Theory of Deep Convolutional Neural Networks for Feature Extraction](http://arxiv.org/abs/1512.06293) (2015)
 +  [Deep Convolutional Neural Networks Based on Semi-Discrete Frames](http://arxiv.org/abs/1504.05487) (2015)
 +  [Unsupervised Learning by Deep Scattering Contractions](http://arxiv.org/abs/1406.2390) (2014)
 +  [Invariant Scattering Convolution Network](http://www.di.ens.fr/data/publications/papers/pami-final.pdf) (2013)
 +  [Group Invariant Scattering](http://arxiv.org/abs/1101.2286) (2011)
 
### Provable Learning of Deep Structure
 +  [Sparse Matrix Factorization](http://arxiv.org/abs/1311.3315) (2013)
 +  [Provable Bounds for Learning Some Deep Representations](http://arxiv.org/abs/1310.6343) (2013)

## Algorithms and Applications 

### Dictionary Learning 
 +  To get a taste of the applications of dictionary learning in signal and image processing (compression in these areas demands good bases/dictionaries), see the book by Michael Elad: [Sparse and Redundant Representations: From Theory to Applications in Signal and Image Processing](https://www.springer.com/mathematics/analysis/book/978-1-4419-7010-7)

### Convolutional Dictionary Learning
 +  [Working Locally Thinking Globally - Part II: Stability and Algorithms for Convolutional Sparse Coding](https://arxiv.org/abs/1607.02009) (2016)
 +  [Working Locally Thinking Globally - Part I: Theoretical Guarantees for Convolutional Sparse Coding](https://arxiv.org/abs/1607.0200) (2016)
 +  [Convolutional Dictionary Learning through Tensor Factorization](http://arxiv.org/abs/1506.03509) (2015)
 +  [Fast Convolutional Sparse Coding](http://www.cv-foundation.org/openaccess/content_cvpr_2013/papers/Bristow_Fast_Convolutional_Sparse_2013_CVPR_paper.pdf) (2013)
 +  [Deconvolutional Network](www.matthewzeiler.com/pubs/cvpr2010/cvpr2010.pdf) (2010)

### Deep Learning
 +  [Scattering Page](http://www.di.ens.fr/data/scattering/) maintained by Stephane Mallat's group


> **Disclaimer** - This page is meant to serve a hub for references on this problem, and does not represent in any way personal endorsement of papers listed here. So I do not hold any responsibility for quality and technical correctness of each paper listed here. The reader is advised to use this resource with discretion.

> **If you'd like your paper to be listed here**  - Just drop me a few lines via email (which can be found on "Welcome" page). If you don't bother to spend a word, just deposit your paper on arXiv. I get email alert about new animals there every morning,  and will be happy to hunt one for this zoo if it seems **fit**. 


