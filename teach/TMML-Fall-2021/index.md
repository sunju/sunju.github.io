---
layout: page
permalink: /teach/TMML-Fall-2021/
title: Topics in Modern Machine Learning
---

### Theme of this iteration

 **theoretical foundations of deep learning**... examines deep learning through the lens of classic and modern approximation, optimization, and learning theory

### Course info

**Syllabus**: [PDF](TMML.pdf)

**Instructor**:  [Professor Ju Sun](https://sunju.org/)  Email: jusun AT umn.edu  

**When/Where**: Mon/Wed 2:30 -- 3:45pm @ Amundson Hall 156

**Office Hours**: Mon/Wed 4 -- 5pm @ Zoom or my office 

### Schedule

General readings: [PNAS Colloquium on The Science of Deep Learning, Dec 2020](https://www.pnas.org/cc/arthur-m-sackler-colloquium-on-the-science-of-deep-learning). The course is organized around six thrusts. 

#### Approximation   
+ Surveys 
  + [Expressivity of Deep Neural Networks](https://arxiv.org/abs/2007.04759)
  + [Neural Network Approximation](https://arxiv.org/abs/2012.14501)
  + Chaps 3--4 of [The Modern Mathematics of Deep Learning](https://arxiv.org/abs/2105.04026)
+ Papers 
  + [Visual proof of universality for shallow networks](http://neuralnetworksanddeeplearning.com/chap4.html)
  + [Approximation theory of the MLP model in neural networks](https://doi.org/10.1017/S0962492900002919) (Survey of UAT focused on shallow networks)
  + [Multilayer feedforward networks are universal
approximators](https://doi.org/10.1016/0893-6080(89)90020-8) (UAT of both deep and shallow networks) 
  + [Universal Function Approximation by Deep Neural Nets with Bounded Width and ReLU Activations](https://arxiv.org/abs/1708.02691) (ReLU networks with bounded width and unbounded depth)
  + [Approximating continuous functions by ReLU nets of minimal width](https://arxiv.org/abs/1710.11278) (ReLU networks with bounded width and unbounded depth)
  + [Error bounds for approximations with deep ReLU networks](https://arxiv.org/abs/1610.01145) (ReLU network approximation of smooth functions)
  + [Error bounds for approximations with deep relu neural networks in $W^{s, p}$ norms](https://arxiv.org/abs/1902.07896) (ReLU network approximation of smooth functions)
  + [Provable approximation properties for deep neural networks](https://arxiv.org/abs/1509.07385) (Approximation of functions on manifolds)
  + [The power of deeper networks for expressing natural functions](https://arxiv.org/abs/1705.05502) (Exponential separation of deep and shallow networks in approximating polynomials)
  + [Benefits of depth in neural networks](https://arxiv.org/abs/1602.04485) (Exponential separation of deep and shallow networks due to composition of ReLU activated layers)
  + [Why and when can deep-but not shallow-networks avoid the curse of dimensionality: A review]( https://doi.org/10.1007/s11633-017-1054-2) (separation of deep and shallow networks on compositional functions)
  + [High-dimensional data analysis: The blessings and curses of dimensionality](Donoho-2000.pdf) (Donoho's 2000 talk on curse/blessing of dimensionality in modern data analysis)
  + [Universal approximations of invariant maps by neural networks](https://arxiv.org/abs/1804.10306) (Approximation of invariant and equivariant functions wrt finite groups)
  + [Equivalence of approximation by convolutional neural networks and fully-connected networks](https://arxiv.org/abs/1809.00973) (Approximation of equivariant functions using CNNs)
+ Further readings 
  + [The gap between theory and practice in function approximation with deep neural networks](https://arxiv.org/abs/2001.07523)
  + [Proof of the Theory-to-Practice Gap in Deep Learning via Sampling Complexity bounds for Neural Network Approximation Spaces](https://arxiv.org/abs/2104.02746)
  + [A deep network construction that adapts to intrinsic dimensionality beyond the domain](https://arxiv.org/abs/2008.02545) (Approximation of functions on manifolds with refined rates)

#### Optimization \& Generalization 
+ Surveys  
  + Chaps 1--2, 5, 6 of [The Modern Mathematics of Deep Learning](https://arxiv.org/abs/2105.04026)
  + [Deep learning: a statistical viewpoint](https://arxiv.org/abs/2103.09177)
  + [Fit without fear: remarkable mathematical phenomena of deep learning through the prism of interpolation](https://arxiv.org/abs/2105.14368)
  + [A Farewell to the Bias-Variance Tradeoff? An Overview of the Theory of Overparameterized Machine Learning](https://arxiv.org/abs/2109.02355)
  
+ Papers
  + [Recent Theoretical Advances in Non-Convex Optimization](https://arxiv.org/abs/2012.06188) (computational complexity of algorithms for nonconvex problems)
  + [Optimization for deep learning: theory and algorithms](https://arxiv.org/abs/1912.08957) (deep learning algorithms, tricks, and theories thereof)
  + [From Symmetry to Geometry: Tractable Nonconvex Problems](https://arxiv.org/abs/2007.06753) (problems that are "essentially" convex up to symmetries)
  + [Accelerated methods for $\alpha$-weakly-quasi-convex problems](https://arxiv.org/abs/1710.00797) (early results on optimizing star-convex functions)
  + [Primal-dual accelerated gradient methods with small-dimensional relaxation oracle](https://arxiv.org/abs/1809.05895) (early results on optimizing star-convex functions)
  + [Near-Optimal Methods for Minimizing Star-Convex Functions and Beyond](https://arxiv.org/abs/1906.11985) (state-of-the-art results on optimizing star-convex functions)
  + [An Alternative View: When Does SGD Escape Local Minima?](https://arxiv.org/abs/1802.06175) (optimizing of neural networks via star convexity)
  + [SGD Converges to Global Minimum in Deep Learning via Star-convex Path](https://arxiv.org/abs/1901.00451) (optimizing of neural networks via star convexity)
  + [Linear Convergence of Gradient and Proximal-Gradient Methods Under the Polyak-Łojasiewicz Condition](https://arxiv.org/abs/1608.04636) (state-of-the-art convergence results based on PL conditions)
  + [On the linearity of large non-linear models: when and why the tangent kernel is constant](https://arxiv.org/abs/2010.01092) (explains when and why model linearization makes sense for nonlinear models)
  + [Loss landscapes and optimization in over-parameterized non-linear systems and neural networks](https://arxiv.org/abs/2003.00307) (non-linear systems and neural networks satisfy the PL conditions under certain conditions)
  + [On Lazy Training in Differentiable Programming](https://arxiv.org/abs/1812.07956) (when and why linearization makes sense, and when not---esp. in practice)
  + [Overparameterized Nonlinear Learning: Gradient Descent Takes the Shortest Path?](https://arxiv.org/abs/1812.10004) (another proof of PL conditions imply global convergence and short optimization paths for undertermined nonlinear models)
  + [Towards moderate overparameterization: global convergence guarantees for training shallow neural networks](https://arxiv.org/abs/1902.04674) (specialization and improvement of the above result for shallow neural networks)
  + [{Euclidean, metric, and Wasserstein} gradient flows: an overview](https://doi.org/10.1007/s13373-017-0101-1) (a nice tutorial on gradient flows)
  + [Computational Optimal Transport](https://arxiv.org/abs/1803.00567) (optimal transport problems, Wasserstein distances, and (Chap 9) Wasserstein gradient flow)
  + [Gradient Descent on Infinitely Wide Neural Networks: Global Convergence and Generalization](https://arxiv.org/abs/2110.08084) (overview of global convergence and generalization of 2-layer NNs using mean-field analysis)
  + [On the Global Convergence of Gradient Descent for Over-parameterized Models using Optimal Transport](https://arxiv.org/abs/1805.09545) (the 1st technical paper behind the above review paper)
  + [Implicit Bias of Gradient Descent for Wide Two-layer Neural Networks Trained with the Logistic Loss](https://arxiv.org/abs/2002.04486) (the 2nd technical paper behind the above review paper)
  + [A Mean Field View of the Landscape of Two-Layers Neural Networks](https://arxiv.org/abs/1804.06561) (complementary mean-field analysis)
  + [Mean-field theory of two-layers neural networks: dimension-free bounds and kernel limit](https://arxiv.org/abs/1902.06015) (complementary mean-field analysis)
  + [A Rigorous Framework for the Mean Field Limit of Multilayer Neural Networks](https://arxiv.org/abs/2001.11443) (mean-field analysis of deep networks)
  + [Introduction to Statistical Learning Theory](https://doi.org/10.1007/978-3-540-28650-9_8) (quick review of classic statistical learning theory)
  + [Theory of Classification: a Survey of Some Recent Advances](https://doi.org/10.1051/ps:2005018) (quick review of more recent developments of statistical learning theory)
  + [Learning without Concentration](https://doi.org/10.1145/2699439) (dealing with heavy-tailed data and functions in learning theory using one-side concentration)
  + [Extending the scope of the small-ball method](https://arxiv.org/abs/1709.00843) (dealing with heavy-tailed data and functions in learning theory using one-side concentration)
  + [Nearly-tight VC-dimension and pseudodimension bounds for piecewise linear neural networks](https://arxiv.org/abs/1703.02930) (state-of-the-art VC dimension results for DNNs)
  + [Rademacher and Gaussian Complexities: Risk Bounds and Structural Results](https://www.jmlr.org/papers/v3/bartlett02a.html) (introduction of Rademacher and Gaussian complexities; Rad complexity of 2-layer NN)
  + [Spectrally-normalized margin bounds for neural networks](https://arxiv.org/abs/1706.08498) (state-of-the-art Rad complexity estimation for DNNs)
  + [Size-Independent Sample Complexity of Neural Networks](https://arxiv.org/abs/1712.06541) (another state-of-the-art Rad complexity estimation for DNNs)
  + [Understanding deep learning (still) requires rethinking generalization](https://doi.org/10.1145/3446776) (distribution-independent bounds unlikely to explain the generalization of DL)
  + [To understand deep learning we need to understand kernel learning](https://arxiv.org/abs/1802.01396) (distribution-dependent bounds may also struggle to explain the generalization of DL)
  + [Uniform convergence may be unable to explain generalization in deep learning](https://arxiv.org/abs/1902.04742) (potential failure of two-sided uniform convergence results for DL)
  + [Failures of model-dependent generalization bounds for least-norm interpolation](https://arxiv.org/abs/2010.08479) (a complementary (stronger) version of the above)

#### Invariance 
+ Surveys 
  + [Geometric Deep Learning: Grids, Groups, Graphs, Geodesics, and Gauges](https://arxiv.org/abs/2104.13478)

#### Robustness 

#### Generation 