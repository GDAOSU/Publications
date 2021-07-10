# Super Resolution of Laser Range Data Based on Image-guided Fusion and Dense Matching
Xu Huang^, Rongjun Qin, Changlin Xiao^, Xiaohu Lu^   
ISPRS Journal of Photogrammetry and Remote Sensing
## Resources
[[PDF]](https://cpb-us-w2.wpmucdn.com/u.osu.edu/dist/4/28638/files/2018/07/LiDAR_and_Image_paper-V3_close_to_final-28lqxo6.pdf)   
## Abstract
Low-cost/real-time laser range scanner is becoming one of the dominant tools in acquiring
accurate 3D point clouds for many smart applications (e.g. automated driving), while the low
point density is often the limiting factor for acquiring fine-scale information. On the other hand,
stereo/multi-stereo images offer considerably higher-resolution 3D data with low cost, while the
image-derived point clouds generally have a higher level of uncertainty. In order to generate
accurate, dense point clouds at a low cost, this paper explores a complementary data fusion of the
low-resolution-high-accuracy laser range data and the high-resolution (high-res) images, and
proposes a super resolution method of laser range data through a novel dense matching framework.
In general, we formulate the super resolution as maximizing a posteriori - Markov random field
(MAP-MRF) problem in a constrained matching framework, where a two-step strategy is
introduced to remove partial inconsistencies between laser range data and images, and the
confidence of the high accuracy laser points are propagated through a uniquely designed path in
the high-resolution image space, such that a global dense matching algorithm can be externally
constrained to yield an accurate, dense and high-fidelity point clouds. We compared the
experiment results of the proposed method with the original laser range data and other two super
resolution methods of laser range data under aerial, terrestrial, and indoor scenarios. These all
demonstrate that the proposed method is capable of producing sub-pixel accuracy, high-fidelity
point clouds, even though the density of laser range data is considerably low (hundreds of times
lower than the image resolutions).  
<p align="center"><img src="https://user-images.githubusercontent.com/32317924/125149204-8953f900-e105-11eb-8620-eb4b14f58faa.png"></p>  
<p align="center"><img src="https://user-images.githubusercontent.com/32317924/125149244-c7511d00-e105-11eb-9f63-6e8270107d39.png"></p>  

## Conclusion
In this paper, we propose a novel super resolution method of laser range data based on image-guided fusion and dense matching, to improve the resolution of laser range data using
high-res stereo images. We formulate the super resolution as the optimization of maximizing a
MAP-MRF problem in a constrained matching framework, and introduce a two-step strategy to
compute an accurate, high-fidelity super resolution result. The main contributions of our method
include: 1) Traditional methods often presume perfect consistency between the laser range data
and images, and our method considers the inconsistencies of the two data sources in the
optimization framework, thus being able to fuse the data even there exists significant
inconsistencies; 2) In the proposed method we devise non-local orthogonal paths for cost
propagation so that the reliable information of each laser point can be fully utilized; 3) The
proposed method conclusively generates accurate, dense and high-fidelity point clouds at a low
cost. 
## Reference
      @article{huang2018super,
        title={Super resolution of laser range data based on image-guided fusion and dense matching},
        author={Huang, Xu and Qin, Rongjun and Xiao, Changlin and Lu, Xiaohu},
        journal={ISPRS Journal of Photogrammetry and Remote Sensing},
        volume={144},
        pages={105--118},
        year={2018},
        publisher={Elsevier}
      }
