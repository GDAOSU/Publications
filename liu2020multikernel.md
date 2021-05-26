# A multi-kernel domain adaptation method for unsupervised transfer learning on cross-source and cross-region remote sensing data classification
Wei Liu^, Rongjun Qin  
IEEE Transactions on Geosciences and Remote Sensing PP(99):1-11
## Resources
[[PDF]](https://ieeexplore.ieee.org/abstract/document/8960415)
## Abstract
Labeling remote sensing data for classification is
labor-intensive and time-consuming. Transfer learning (TL),
under such context, is attracting increasing attention as it aims
to harness information from data set of other regions where
labels are readily available. The central topic of concern is
to homogenize the large disparities of feature distribution of
different data set through domain adaptation (DA). This article
proposes a novel DA method for unsupervised TL, namely, multikernel jointly domain matching (MKJDM), which by definition
considers multiple kernels as opposed to the currently popular
single-kernel methods for measuring the distances between distributions. The single-kernel methods minimize the distances of
feature distribution between the source domain (data set with
training labels) and the target domain (data set to be classified)
through, for example, maximum mean discrepancy (MMD)
metric, formed under a kernel function mapping, while the
multikernel version (MK-MMD) uses different kernel functions
to encapsulate multiple aspects of distribution discrepancies,
and is, therefore, more capable of distance minimization. Our
MKJDM implementation also considers simultaneously aligning
marginal and class conditional distributions and reweight for
each instance, which further improves the performance. Two
experiments performed on remote sensing images and multimodal data sets (i.e., Orthophoto and Digital Surface Models),
with regions of different countries with distinctly different land
patterns serving as source and target domain data, show that
the overall accuracies are improved by 37.28% and 46.62% after
applications of our MKJDM method. An additional comparative
experiment with five state-of-the-art DA methods also demonstrates that our method achieves the best performance



<p align="center"><img src="https://user-images.githubusercontent.com/32317924/119673307-4108a200-be09-11eb-8093-65a7ac2754fc.png"></p>
<p align="center"><img src="https://user-images.githubusercontent.com/32317924/119674629-5af6b480-be0a-11eb-8f86-691de733632a.png"></p>
<p align="center"><img src="https://user-images.githubusercontent.com/32317924/119674781-7cf03700-be0a-11eb-8087-bbcb4d814d2e.png"></p>

## Conclusion
In this article, we propose a novel unsupervised DA method,
namely, MKJDM method. The proposed method is applied
to the multi-modal remote sensing data set (Orthophoto +
DSM) and the multi-spectral data set (with DSM). Based on
our experiments, the proposed method achieved satisfactory
results and has a promising potential to significantly reduce
the label cost in classifying remote sensing images. To align
the distributions of the source and target feature domains,
our method considers formulating both marginal distribution
and conditional distribution under an MK-MMD measure in
a single optimization step. In addition, our proposed method
reweights instances belonging to certain classes in the source
domain to enhance the robustness of the feature distribution
alignment. The solution of the formulated optimization delivers a transformation matrix which is used to map the feature
sets of the source and target domains into RKHS can be computed, and the resulting feature distributions of the source and
target domain are more statistically close. A simple statistical
classifier using the transformed features for classification is
able to acquire satisfactory results. As compared to other stateof-the-art DA methods, the proposed method obtained the best
results in our experiments, and in the best case, has obtained
47% improvement as compared to a nontransferred classifier.
Our experiment data sets of cross-continental regions suggest
the practical potentials in using the unsupervised method for
classification of remote sensing data through DA-based TL. In
future works, we will consider including more stable features
of the multi-modal to further improve the performance of the
classification and reduce its computational complexity for the
application to large-format remote sensing images.


## Referece
    @article{liu2020multikernel,
      title={A multikernel domain adaptation method for unsupervised transfer learning on cross-source and cross-region remote sensing data classification},
      author={Liu, Wei and Qin, Rongjun},
      journal={IEEE Transactions on Geoscience and Remote Sensing},
      volume={58},
      number={6},
      pages={4279--4289},
      year={2020},
      publisher={IEEE}
    }
