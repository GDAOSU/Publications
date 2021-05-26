# Bispace Domain Adaptation Network for Remotely Sensed Semantic Segmentation
Liu, Wei, Fulin Su, Xinfei Jin, Hongxu Li, and Rongjun Qin.  
IEEE Transactions on Geoscience and Remote Sensing (2020)

## Resources
[[PDF]](https://ieeexplore.ieee.org/abstract/document/9261997?casa_token=J2oj2x5hPe0AAAAA:GjnZQ2VgeUia-RNfFD7c058Dyy7RNbUE-n4_y8OHUnB9aAoJUCoEgHVJeb_zsseIH8xKubwK)

## Abstract
Supervised learning for semantic segmentation has
achieved impressive success in remote sensing, while this normally has a high demand on pixel-level ground truth from
the testing images (target domain). Labeling data for semantic
segmentation is labor-intensive and time-consuming. To reduce
the workload of manual labeling, domain adaptation (DA) utilizes
preexisting labeled images from other sources (source domain)
to classify the images in the target domain. In this article,
we propose a bispace alignment network for DA named BSANet.
BSANet is designed to have a dual-branch structure which is
able to extract features in the image domain and the wavelet
domain simultaneously. To minimize the discrepancy between
the source and target domains, we propose a bispace adversarial
learning strategy. Specifically, BSANet employs two discriminators in different spaces, one aligning the source and target
feature distributions, and the other helping the classification
outputs render reasonable spatial layouts. The proposed method
shows the ability to train an end-to-end network for semantic
segmentation without using any label in the target domain.
Extensive experiments and ablation studies are conducted in
cross-city scenarios. Comparative experiments with several stateof-the-art DA methods show that our method achieves the best
performance.

<p align="center"><img src="https://user-images.githubusercontent.com/32317924/119669818-5a5c1f00-be06-11eb-9593-de506d9a2ac1.png"></p>
<p align="center"><img src="https://user-images.githubusercontent.com/32317924/119669963-7fe92880-be06-11eb-872d-fe2c5efa3f4b.png"></p>
<p align="center"><img src="https://user-images.githubusercontent.com/32317924/119670571-fdad3400-be06-11eb-9ab8-ffe1c1f84cf6.png"></r>

## Conclusion
In this article, we propose an end-to-end unsupervised DA
network named BSANet for semantic segmentation. BSANet
aims to avoid labeling efforts when there is a large difference
between the source and target domains. By embedding wavelet
transform into a branch of BSANet, the dual-branch structure
of BSANet is able to extract features from the wavelet and
image domains at the same time. Utilizing two discriminators
to, respectively, minimize the discrepancy in fused feature
spaces and output spaces, our proposed bispace adversarial
learning strategy is able to further improve the DA performance. The experiments show that BSANet achieves dramatically improvements under different scenarios. The ablation
study demonstrates that both the two main innovations of the
proposed method are effective. In future works, we plan to explore how to combine the ideas of style transfer and bispace
adversarial learning.
## Reference
    @ARTICLE{9261997,
      author={Liu, Wei and Su, Fulin and Jin, Xinfei and Li, Hongxu and Qin, Rongjun},
      journal={IEEE Transactions on Geoscience and Remote Sensing}, 
      title={Bispace Domain Adaptation Network for Remotely Sensed Semantic Segmentation}, 
      year={2020},
      volume={},
      number={},
      pages={1-11},
      doi={10.1109/TGRS.2020.3035561}}
  
