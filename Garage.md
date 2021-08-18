# A volumetric change detection framework using UAV oblique photogrammetry – a case study of ultra-high-resolution monitoring of progressive building collapse
Xu, Ningli, Debao Huang, Shuang Song, Xiao Ling, Chris Strasbaugh, Alper Yilmaz, Halil Sezen, and Rongjun Qin   
International Journal of Digital Earth
## Resources
[[PDF]](https://u.osu.edu/qin.324/files/2021/08/IJDE_main_final_preprint.pdf)   
[[VIDEO]](https://youtu.be/uLaLV6Q5El0) 
## Abstract
  In this paper, we present a case study that performs an unmanned aerial
vehicle (UAV) based fine-scale 3D change detection and monitoring of
progressive collapse performance of a building during a demolition
event. Multi-temporal oblique photogrammetry images are collected
with 3D point clouds generated at different stages of the demolition.
The geometric accuracy of the generated point clouds has been
evaluated against both airborne and terrestrial LiDAR point clouds,
achieving an average distance of 12 cm and 16 cm for roof and façade
respectively. We propose a hierarchical volumetric change detection
framework that unifies multi-temporal UAV images for pose estimation
(free of ground control points), reconstruction, and a coarse-to-fine 3D
density change analysis. This work has provided a solution capable of
addressing change detection on full 3D time-series datasets where
dramatic scene content changes are presented progressively. Our
change detection results on the building demolition event have been
evaluated against the manually marked ground-truth changes and have
achieved an F-1 score varying from 0.78 to 0.92, with consistently high
precision (0.92–0.99). Volumetric changes through the demolition
progress are derived from change detection and have been shown to
favorably reflect the qualitative and quantitative building demolition
progression.
![_7~J{64 8(`8)QMTM0(VBK9](https://user-images.githubusercontent.com/32317924/129952786-247ee855-bbfa-4bdc-9e19-57a4b9360ad6.png)
![019(RGP_N(WL(98C{FZV 1M](https://user-images.githubusercontent.com/32317924/129953168-5bfc430b-61bc-4b76-810d-02cbb61b6a45.png)
![QQ1$E$)J~KWSOOM}9M5E2GB](https://user-images.githubusercontent.com/32317924/129952963-5a5881c3-6dfc-400c-8491-eb090c93e7ac.png)
![$ ~5WLRL515P17W6}%(0TI9](https://user-images.githubusercontent.com/32317924/129953180-d067f717-32e7-4daa-88ba-a4567c087f66.png)
## Conclusion
  In this paper, we presented an end-to-end workflow for 3D change detection using time-series
UAV-oblique images. The idea is to perform a fully automated progressive bundle adjustment
and a coarse-to-fine 3D volumetric change detection framework to locate and identify the volume
of changes. The proposed progressive bundle adjustment follows and advances existing 3D implicit
registration paradigms to allow 3D collections to be robustly registered for evaluation, and the
octree-based volumetric change detection algorithm with a 3D density change vector is specifically
designed to reduce false positives commonly presented in change detection to ensure high
precision.
The proposed workflow is validated on a case study of building demolition event through progressive collapse, in which two adjacent five-story parking garage structures (with approximately
35,000 square meters of footage) underwent a demolition process and UAV-oblique photogrammetric images are collected under a constrained collection environment, repetitively on six separate
days throughout the one-month demolition period. Our work has validated the proposed approach
through the following three aspects:  
  (1) We evaluated the generated UAV point clouds through cloud-to-cloud distance with airborne
and terrestrial LiDAR point clouds and concluded that our collection configuration (as introduced in Section 4.1) yields point clouds with an accuracy of 12 cm on the roof structure and
16 cm on the façade structure.  
  (2) We evaluated the proposed hierarchical change detection algorithm against the selected regions
where ground-truth changes are manually labeled and achieved an F-1 score varying from 0.78
to 0.92, with consistently high precision (0.92–0.99), which is suitable to identify focused
changes occurring in a progressive manner.  
  (3) We calculated the volumetric changes using the collected data and demonstrated that the
derived statistics such as the total volume of change and the demolition rate may serve as useful
information for construction management or for assessment of structures that may be
damaged or partially collapsed after a man-made or natural disaster.  
  We consider this work has presented a useful workflow and a full-scale case study that will provide useful knowledge to potential researchers and engineers for such ultra-high-resolution monitoring tasks using UAV-oblique photogrammetry. In our work, we noted the drawbacks of this
method still lies in the lack of control of octree depth, as well as a more accurate presentation
for volumetric calculation under cases where partial occlu
## Reference
    @article{xu2021volumetric,
      title={A volumetric change detection framework using UAV oblique photogrammetry--a case study of ultra-high-resolution monitoring of progressive building collapse},
      author={Xu, Ningli and Huang, Debao and Song, Shuang and Ling, Xiao and Strasbaugh, Chris and Yilmaz, Alper and Sezen, Halil and Qin, Rongjun},
      journal={International Journal of Digital Earth},
      pages={1--16},
      year={2021},
      publisher={Taylor \& Francis}
    }
