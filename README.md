# Awesome Optimal Transport
A list of awesome papers and cool resources on optimal transport (OT) and its applications in general! As you will notice, this list is currently mostly focused on optimal transport for machine learning topics.


# Table of Contents

* [Tutorial and Blogs](#tutorials-and-blogs)
* [Libraries](#libraries)
* [Books](#books)
* [Papers](#papers)
  * [Fast approximation Optimal Transport](#fast-approximation-optimal-transport)
    * [Approximation Optimal Transport](#approximating-optimal-transport)
    * [Regularized Optimal Transport](#regularized-optimal-transport)
    * [Sliced Optimal Transport](#sliced-optimal-transport)
  * [Unbalanced Optimal Transport](#unbalanced-optimal-transport)
  * [Curse of dimension](#curse-of-dimension)
  * [Wasserstein barycenters](#wasserstein-barycenters)
  * [Generative Models](#generative-models)
  * [Domain Adaptations](#domain-adaptation)
  * [Adversarial Robustness](#adversarial-robustness)

# Tutorials and Blogs

* [Course notes on Optimal Transport - MVA master ENS Paris-Saclay](https://optimaltransport.github.io/slides-peyre/CourseOT.pdf)
* [Optimal Transport tutorial](http://remi.flamary.com/cours/tuto_otml.html)

# Libraries

* [POT: Python Optimal Transport](https://pythonot.github.io/) (Python Optimal Transport library)
* [Geomloss](https://www.kernel-operations.io/geomloss/) (Pytorch library of regularized OT loss variants)  | [GitHub Repo](https://github.com/jeanfeydy/geomloss)

# Books

* [Computational Optimal Transport](https://optimaltransport.github.io/) | [Arxiv](https://arxiv.org/abs/1803.00567)
* [Optimal Transport for Applied Mathematicians](https://www.imo.universite-paris-saclay.fr/~filippo/OTAM-cvgmt.pdf)


# Papers

Papers are ordered by theme and inside each theme by publication date (accepted papers only).

## Fast approximation Optimal Transport

Fast Optimal Transport problems

### Approximating Optimal Transport

Fast approximation of Optimal Transport problems

 * [Learning with minibatch Wasserstein : asymptotic and gradient properties](http://proceedings.mlr.press/v108/fatras20a.html) (AISTATS 2020) | [Code](https://github.com/kilianFatras/minibatch_Wasserstein)
 * [Hierarchical Optimal Transport for Multimodal Distribution Alignment](https://papers.nips.cc/paper/9501-hierarchical-optimal-transport-for-multimodal-distribution-alignment) (NeurIPS 2019)
 * [Optimal Transport: Fast Probabilistic Approximation with Exact Solvers](http://www.jmlr.org/papers/volume20/18-079/18-079.pdf) (JMLR 2019)
 * [Multiscale Strategies for Computing Optimal Transport](https://jmlr.csail.mit.edu/papers/volume18/16-108/16-108.pdf) (JMLR 2017)

### Regularized Optimal Transport

Regularized Optimal Transport and solvers

 * [Stochastic Optimization for Regularized Wasserstein Estimators](https://arxiv.org/abs/2002.08695) (ICML 2020)
 * [Regularized Optimal Transport is Ground Cost Adversarial](https://arxiv.org/pdf/2002.03967.pdf) (ICML 2020)
 * [Interpolating between Optimal Transport and MMD using Sinkhorn Divergences](http://proceedings.mlr.press/v89/feydy19a) (AISTATS 2019) | [Code](https://github.com/jeanfeydy/geomloss)
 * [Differential Properties of Sinkhorn Approximation for Learning with Wasserstein Distance](http://papers.nips.cc/paper/7827-differential-properties-of-sinkhorn-approximation-for-learning-with-wasserstein-distance) (NeurIPS 2018)
 * [Smooth and Sparse Optimal Transport](http://proceedings.mlr.press/v84/blondel18a) (AISTATS 2018) | [Code](https://pythonot.github.io/gen_modules/ot.smooth.html#module-ot.smooth)
 * [Near-linear time approximation algorithms for optimal transport via Sinkhorn iteration](https://papers.nips.cc/paper/6792-near-linear-time-approximation-algorithms-for-optimal-transport-via-sinkhorn-iteration) (NeurIPS 2017) | [Code](https://pythonot.github.io/gen_modules/ot.bregman.html)
 * [Stochastic Optimization for Large-scale Optimal Transport](https://papers.nips.cc/paper/6566-stochastic-optimization-for-large-scale-optimal-transport.pdf) (NeurIPS 2016) | [Code](https://pythonot.github.io/gen_modules/ot.stochastic.html#module-ot.stochastic)
 * [Regularized Discrete Optimal Transport](https://arxiv.org/pdf/1307.5551.pdf) (SIAM Journal on Imaging Sciences 2014)
 * [Sinkhorn Distances: Lightspeed Computation of Optimal Transport](https://papers.nips.cc/paper/4927-sinkhorn-distances-lightspeed-computation-of-optimal-transport) (NeurIPS 2013)

### Sliced Optimal Transport

Sliced Optimal Transport (averaged of 1D projections)

* [Sliced Gromov-Wasserstein](https://papers.nips.cc/paper/9615-sliced-gromov-wasserstein) (NeurIPS 2019) | [Code](https://github.com/tvayer/SGW)
* [Generalized Sliced Wasserstein Distances](https://papers.nips.cc/paper/8319-generalized-sliced-wasserstein-distances) (NeurIPS 2019)
* [Max-Sliced Wasserstein Distance and Its Use for GANs](https://openaccess.thecvf.com/content_CVPR_2019/html/Deshpande_Max-Sliced_Wasserstein_Distance_and_Its_Use_for_GANs_CVPR_2019_paper.html) (CVPR 2019)
* [Sliced Wasserstein kernels for probability distributions](https://openaccess.thecvf.com/content_cvpr_2016/papers/Kolouri_Sliced_Wasserstein_Kernels_CVPR_2016_paper.pdf) (CVPR 2016)

## Unbalanced and Partial Optimal Transport

Unbalanced and Partial Optimal Transport variants
* [Partial Gromov-Wasserstein with applications on Positive-Unlabeled Learning](https://arxiv.org/abs/2002.08276) (NeurIPS 2020) | [Code](https://github.com/lchapel/partial-GW-for-PU)
* [Robust Optimal Transport with Applications in Generative Modeling and Domain Adaptation](https://arxiv.org/abs/2010.05862) (NeurIPS 2020) | [Code](https://github.com/yogeshbalaji/robustOT)
* [On Unbalanced Optimal Transport: An Analysis of Sinkhorn Algorithm](https://arxiv.org/abs/2002.03293) (ICML 2020)
* [Scaling Algorithms for Unbalanced Transport Problems](https://arxiv.org/abs/1607.05816) (Mathematics of Computation 2018)
* [Unbalanced Optimal Transport: Dynamic and Kantorovich formulations](https://www.sciencedirect.com/science/article/pii/S0022123618301058) (Journal of Functional Analysis 2018) | [Code](https://pythonot.github.io/gen_modules/ot.unbalanced.html)

## Curse of dimension

Theoretical insights and Optimal Transport variants to tackle the curse of dimension.

* [Gaussian-Smoothed Optimal Transport: Metric Structure and Statistical Efficiency](http://proceedings.mlr.press/v108/goldfeld20a.html) (AISTATS 2020)
* [Statistical bounds for entropic optimal transport: sample complexity and the central limit theorem](https://papers.nips.cc/paper/8703-statistical-bounds-for-entropic-optimal-transport-sample-complexity-and-the-central-limit-theorem) (NeurIPS2019)
* [Subspace Detours: Building Transport Plans that are Optimal on Subspace Projections](http://papers.nips.cc/paper/8915-subspace-detours-building-transport-plans-that-are-optimal-on-subspace-projections) (NeurIPS 2019)
* [Subspace Robust Wasserstein Distances](http://proceedings.mlr.press/v97/paty19a.html) (ICML 2019) | [Code](https://github.com/francoispierrepaty/SubspaceRobustWasserstein)
* [Sample Complexity of Sinkhorn Divergences](http://proceedings.mlr.press/v89/genevay19a.html) (AISTATS 2019)
* [Sharp asymptotic and finite-sample rates of convergence of empirical measures in Wasserstein distance](https://projecteuclid.org/euclid.bj/1568362038) (Bernoulli 2019)

## Wasserstein barycenters

Wasserstein barycenters applications

* [Sinkhorn Barycenters with Free Support via Frank-Wolfe Algorithm](https://papers.nips.cc/paper/9130-sinkhorn-barycenters-with-free-support-via-frank-wolfe-algorithm.pdf) (NeurIPS 2019)
* [On the Complexity of Approximating Wasserstein Barycenters](http://proceedings.mlr.press/v97/kroshnin19a.html) (ICML 2019)
* [Decentralize and Randomize: Faster Algorithm for Wasserstein Barycenters](http://papers.nips.cc/paper/8274-decentralize-and-randomize-faster-algorithm-for-wasserstein-barycenter) (NeurIPS 2018)
* [Stochastic Wasserstein Barycenters](http://proceedings.mlr.press/v80/claici18a/claici18a.pdf) (ICML 2018)
* [Parallel Streaming Wasserstein Barycenters](http://papers.nips.cc/paper/6858-parallel-streaming-wasserstein-barycenters) (NeurIPS 2017)
* [Fast Computation of Wasserstein Barycenters](http://proceedings.mlr.press/v32/cuturi14.html) (ICML 2014)
* [Wasserstein Barycenter and Its Application to Texture Mixing](https://hal.archives-ouvertes.fr/hal-00476064/document) (SSVM 2011)

## Generative models

Optimal Transport for Generative Models

 * [Learning Generative Models across Incomparable Spaces](http://proceedings.mlr.press/v97/bunne19a) (ICML 2019) | [Code](https://github.com/bunnech/gw_gan)
 * [Sliced-Wasserstein Flows: Nonparametric Generative Modeling via Optimal Transport and Diffusions](http://proceedings.mlr.press/v97/liutkus19a) (ICML 2019) | [Code](https://github.com/aliutkus/swf)
 * [Sliced Wasserstein Generative Models](https://openaccess.thecvf.com/content_CVPR_2019/html/Wu_Sliced_Wasserstein_Generative_Models_CVPR_2019_paper.html) (CVPR 2019)
 * [OT-GAN: Improving GANs Using Optimal Transport ](https://openreview.net/forum?id=rkQkBnJAb) (ICLR 2018) | [Code](https://github.com/openai/ot-gan)
 * [Learning Generative Models with Sinkhorn Divergences](http://proceedings.mlr.press/v84/genevay18a.html) (AISTATS 2018)
 * [WGAN-GP: Improved Training of Wasserstein GANs](https://papers.nips.cc/paper/7159-improved-training-of-wasserstein-gans) (NeurIPS 2017)
 * [WGAN: Wasserstein Generative Adversarial Networks](http://proceedings.mlr.press/v70/arjovsky17a.html) (NeurIPS 2017)

## Domain adaptations

Optimal Transport for Domain Adaptations
* [Margin-aware Adversarial Domain Adaptation with Optimal Transport](https://hal.archives-ouvertes.fr/hal-02900715) (ICML 2020)
* [Joint Partial Optimal Transport for Open Set Domain Adaptation](https://www.ijcai.org/Proceedings/2020/0352.pdf) (IJCAI 2020)
* [Sliced Wasserstein Discrepancy for Unsupervised Domain Adaptation](https://openaccess.thecvf.com/content_CVPR_2019/html/Lee_Sliced_Wasserstein_Discrepancy_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.html) (CVPR 2019)
* [Optimal Transport for Multi-source Domain Adaptation under Target Shift](http://proceedings.mlr.press/v89/redko19a.html) (AISTATS 2019)
* [Differentially Private Optimal Transport: Application to Domain Adaptation](https://www.ijcai.org/Proceedings/2019/0395) (IJCAI 2019)
* [DeepJDOT: Deep Joint Distribution Optimal Transport for Unsupervised Domain Adaptation](https://openaccess.thecvf.com/content_ECCV_2018/html/Bharath_Bhushan_Damodaran_DeepJDOT_Deep_Joint_ECCV_2018_paper.html) (ECCV 2018) | [Code](https://github.com/bbdamodaran/deepJDOT)
* [Wasserstein Distance Guided Representation Learning for Domain Adaptation](https://arxiv.org/abs/1707.01217) (AAAI 2018) | [Code](https://github.com/RockySJ/WDGRL)
* [Joint distribution optimal transportation for domain adaptation](https://papers.nips.cc/paper/6963-joint-distribution-optimal-transportation-for-domain-adaptation) (NeurIPS2017) | [Code](https://github.com/rflamary/JDOT)
* [Optimal Transport for Domain Adaptation](https://arxiv.org/abs/1507.00504) (TPAMI 2017)

## Adversarial robustness

Papers on Adversarial robustness using Wasserstein distance

* [Stronger and Faster Wasserstein Adversarial Attacks](https://arxiv.org/abs/2008.02883) (ICML 2020)
* [Wasserstein Smoothing: Certified Robustness against Wasserstein Adversarial Attacks](http://proceedings.mlr.press/v108/levine20a.html) (AISTATS 2020)
* [Wasserstein Adversarial Examples via Projected Sinkhorn Iterations](http://proceedings.mlr.press/v97/wong19a) (ICML 2019)
