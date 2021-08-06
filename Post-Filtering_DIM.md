# Post-Filtering with Surface Orientation Constraints for Stereo Dense Image Matching
Xu Huang^, Rongjun Qin  
The Photogrammetric Record
## Resources
[[PDF]](https://onlinelibrary.wiley.com/doi/full/10.1111/phor.12333)  
[[CODE]](https://github.com/GDAOSU/Post-Filtering)  
## Abstract
Dense image matching (DIM) is a critical technique when computing accurate 3D geometric information for many photogrammetric applications. Most DIM methods adopt first-order regularisation priors for efficient matching, which often introduce stepped biases (also called fronto-parallel biases) into the matching results. To remove these biases and compute more accurate matching results, this paper proposes a novel post-filtering method by adjusting the surface orientation of each pixel in the matching process. The core algorithm formulates the post-filtering as the optimisation of a global energy function with second-order regularisation priors. A compromise solution of the energy function is computed by breaking the optimisation into a collection of sub-optimisations of each pixel in a local adaptive window. The proposed method was compared with several state-of-the-art post-filtering methods on indoor, aerial and satellite datasets. The comparisons demonstrate that the proposed method obtains the highest post-filtering accuracies on all datasets.
![$PYS%R~}HVMM@@%13Y}IT3N](https://user-images.githubusercontent.com/32317924/128572899-4dd892a0-ef05-465c-8f78-e37e8679367f.png)  
![TF OGIS)~V`OCVCRASQ9LYC](https://user-images.githubusercontent.com/32317924/128573181-98bc2165-deef-4bd2-a938-34ee73b36cac.png)


## Conclusion
In this paper, a novel post-filtering method is proposed based on surface orientationconstraints to remove fronto-parallel biases in the matching results of 1D DIM methods.The post-filtering is formulated as the minimisation of a global energy function andintroduces a compromise solution by breaking the optimisation into a collection of sub-optimisations of each pixel in a local adaptive window. The main contributions of theproposed method include:(1) Some state-of-the-art post-filtering methods (such as bilateralfiltering and guidedimagefiltering) may introduce some artefacts into thefiltering results, while theproposed method is capable of computing smoother surfaces.(2) The proposed method considers an adaptivefiltering window that is able topreserve sharp boundaries infiltering results.(3) The proposed method is able to compute smooth surfaces with highfilteringaccuracies.Experiments on indoor, aerial and satellite datasets demonstrated that the proposedmethod outperforms the state-of-the-art post-filtering methods (BF, GF, MF and MLPA) inalmost all cases. It was also observed that the computational cost of the proposed methodmainly focuses on the adaptive window definition (for example, 33⋅031 s in the secondexperiment). In future work, the authors plan to reduce the computational cost by applyingmore efficient window definition techniques, for example, an integral map
## Reference
    @article{huang2020post,
      title={Post-filtering with surface orientation constraints for stereo dense image matching},
      author={Huang, Xu and Qin, Rongjun},
      journal={The Photogrammetric Record},
      volume={35},
      number={171},
      pages={375--401},
      year={2020},
      publisher={Wiley Online Library}
    }
