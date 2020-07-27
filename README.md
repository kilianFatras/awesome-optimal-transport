# Awesome Optimal Transport
A list of awesome papers and cool resources on optimal transport (OT) and its applications in general! As you will notice, this list is currently mostly focused on optimal transport for machine learning topics.


# Table of Contents

* [Tutorial and Blogs](#tutorials-and-blogs)
* [Libraries](#libraries)
* [Books](#books)
* [Papers](#papers)
  * [Fast approximation Optimal Transport](#fast-approximation-optimal-transport)
    * [Approximation Optimal Transport](#approximation-optimal-transport)
    * [Regularized Optimal Transport](#regularized-optimal-transport)
    * [Sliced Optimal Transport](#sliced-optimal-transport)
  * [Generative Models](#generative-models)
  * [Domain Adaptations](#domain-adaptation)

# Tutorials and Blogs

* [Course notes on Optimal Transport - MVA master ENS Paris-Saclay](https://optimaltransport.github.io/slides-peyre/CourseOT.pdf)
* [Optimal Transport tutorial](http://remi.flamary.com/cours/tuto_otml.html)

# Libraries

* [POT: Python Optimal Transport](https://pythonot.github.io/)
* [Geomloss](https://www.kernel-operations.io/geomloss/) (Pytorch library of regularized OT loss variants)  | [GitHub Repo](https://github.com/jeanfeydy/geomloss)

# Books

* [Computational Optimal Transport](https://optimaltransport.github.io/) | [Arxiv](https://arxiv.org/abs/1803.00567)
* [Optimal Transport for Applied Mathematicians](https://www.imo.universite-paris-saclay.fr/~filippo/OTAM-cvgmt.pdf)


# Papers

Papers are ordered by theme and inside each theme by publication date (accepted papers only).

## Fast approximation Optimal Transport

Fast approximation of Optimal Transport problems

### Approximation of Optimal Transport problems

 * [Learning with minibatch Wasserstein : asymptotic and gradient properties](http://proceedings.mlr.press/v108/fatras20a.html) (2020)
 * [Hierarchical Optimal Transport for Multimodal Distribution Alignment](https://papers.nips.cc/paper/9501-hierarchical-optimal-transport-for-multimodal-distribution-alignment) (2019)
 * [Optimal Transport: Fast Probabilistic Approximation with Exact Solvers](http://www.jmlr.org/papers/volume20/18-079/18-079.pdf) (2019)
 * [Multiscale Strategies for Computing Optimal Transport](https://jmlr.csail.mit.edu/papers/volume18/16-108/16-108.pdf) (2017)

### Regularized Optimal Transport

Regularized Optimal Transport and solvers

 * [Stochastic Optimization for Regularized Wasserstein Estimators](https://arxiv.org/abs/2002.08695) (2020)
 * [Interpolating between Optimal Transport and MMD using Sinkhorn Divergences](http://proceedings.mlr.press/v89/feydy19a) (2019) | [Code](https://github.com/jeanfeydy/geomloss)
 * [Sample Complexity of Sinkhorn Divergences](http://proceedings.mlr.press/v89/genevay19a.html) (2019)
 * [Smooth and Sparse Optimal Transport](http://proceedings.mlr.press/v84/blondel18a) (2018) | [Code](https://pythonot.github.io/gen_modules/ot.smooth.html#module-ot.smooth)
 * [Near-linear time approximation algorithms for optimal transport via Sinkhorn iteration](https://papers.nips.cc/paper/6792-near-linear-time-approximation-algorithms-for-optimal-transport-via-sinkhorn-iteration) (2017) | [Code](https://pythonot.github.io/gen_modules/ot.bregman.html)
 * [Stochastic Optimization for Large-scale Optimal Transport](https://papers.nips.cc/paper/6566-stochastic-optimization-for-large-scale-optimal-transport.pdf) (2016) | [Code](https://pythonot.github.io/gen_modules/ot.stochastic.html#module-ot.stochastic)
 * [Regularized Discrete Optimal Transport](https://arxiv.org/pdf/1307.5551.pdf)
 * [Sinkhorn Distances: Lightspeed Computation of Optimal Transport](https://papers.nips.cc/paper/4927-sinkhorn-distances-lightspeed-computation-of-optimal-transport) (2013)

### Sliced Optimal Transport
* [Sliced Gromov-Wasserstein](https://papers.nips.cc/paper/9615-sliced-gromov-wasserstein) (2019) | [Code](https://github.com/tvayer/SGW)
* [Generalized Sliced Wasserstein Distances](https://papers.nips.cc/paper/8319-generalized-sliced-wasserstein-distances) (2019)
* [Max-Sliced Wasserstein Distance and Its Use for GANs](https://openaccess.thecvf.com/content_CVPR_2019/html/Deshpande_Max-Sliced_Wasserstein_Distance_and_Its_Use_for_GANs_CVPR_2019_paper.html) (2019)

## Generative Models

Optimal Transport for Generative Models
 * [Learning Generative Models across Incomparable Spaces](http://proceedings.mlr.press/v97/bunne19a) (2019) | [Code](https://github.com/bunnech/gw_gan)
 * [Sliced-Wasserstein Flows: Nonparametric Generative Modeling via Optimal Transport and Diffusions](http://proceedings.mlr.press/v97/liutkus19a) (2019) | [Code](https://github.com/aliutkus/swf)
 * [Sliced Wasserstein Generative Models](https://openaccess.thecvf.com/content_CVPR_2019/html/Wu_Sliced_Wasserstein_Generative_Models_CVPR_2019_paper.html) (2019)
 * [OT-GAN: Improving GANs Using Optimal Transport ](https://openreview.net/forum?id=rkQkBnJAb) (2018) | [Code](https://github.com/openai/ot-gan)
 * [Learning Generative Models with Sinkhorn Divergences](http://proceedings.mlr.press/v84/genevay18a.html) (2018)
 * [WGAN-GP: Improved Training of Wasserstein GANs](https://papers.nips.cc/paper/7159-improved-training-of-wasserstein-gans) (2017)
 * [WGAN: Wasserstein Generative Adversarial Networks](http://proceedings.mlr.press/v70/arjovsky17a.html) (2017)

## Domain Adaptations

Optimal Transport for Domain Adaptations
* [Sliced Wasserstein Discrepancy for Unsupervised Domain Adaptation](https://openaccess.thecvf.com/content_CVPR_2019/html/Lee_Sliced_Wasserstein_Discrepancy_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.html) (2019)
* [Optimal Transport for Multi-source Domain Adaptation under Target Shift](http://proceedings.mlr.press/v89/redko19a.html) (2019)
* [DeepJDOT: Deep Joint Distribution Optimal Transport for Unsupervised Domain Adaptation](https://openaccess.thecvf.com/content_ECCV_2018/html/Bharath_Bhushan_Damodaran_DeepJDOT_Deep_Joint_ECCV_2018_paper.html) (2018) | [Code](https://github.com/bbdamodaran/deepJDOT)
* [Joint distribution optimal transportation for domain adaptation](https://papers.nips.cc/paper/6963-joint-distribution-optimal-transportation-for-domain-adaptation) (2017) | [Code](https://github.com/rflamary/JDOT)
* [Optimal Transport for Domain Adaptation](https://arxiv.org/abs/1507.00504) (2017)
