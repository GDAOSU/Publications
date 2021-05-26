# Geometry-Aware Satellite-to-Ground Image Synthesis for Urban Areas
Lu, Xiaohu, Zuoyue Li, Zhaopeng Cui, Martin R. Oswald, Marc Pollefeys, and Rongjun Qin  
In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pp. 859-867. 2020.
## Resources
[[CODE]](https://github.com/lizuoyue/sate_to_ground)  
[[PDF]](https://openaccess.thecvf.com/content_CVPR_2020/html/Lu_Geometry-Aware_Satellite-to-Ground_Image_Synthesis_for_Urban_Areas_CVPR_2020_paper.html)

## Abstract
We present a novel method for generating panoramic
street-view images which are geometrically consistent with
a given satellite image. Different from existing approaches
that completely rely on a deep learning architecture to generalize cross-view image distributions, our approach explicitly loops in the geometric configuration of the ground objects based on the satellite views, such that the produced
ground view synthesis preserves the geometric shape and
the semantics of the scene. In particular, we propose a
neural network with a geo-transformation layer that turns
predicted ground-height values from the satellite view to a
ground view while retaining the physical satellite-to-ground
relation. Our results show that the synthesized image retains well-articulated and authentic geometric shapes, as
well as texture richness of the street-view in various scenarios. Both qualitative and quantitative results demonstrate
that our method compares favorably to other state-of-theart approaches that lack geometric consistency.
<p><img src="https://user-images.githubusercontent.com/32317924/119601788-e561f880-bdb7-11eb-8fbe-47492d825263.png"></p>
<p align="center"><img src="https://user-images.githubusercontent.com/32317924/119601864-075b7b00-bdb8-11eb-992c-f63ec71ffc9b.png"></p>
<p align="center"><img src="https://user-images.githubusercontent.com/32317924/119602838-0c212e80-bdba-11eb-9c4a-1954105c1f34.png"></p>





## Conclusion
We presented a novel approach for satellite-to-ground
cross-view synthesis. In particular, we proposed an endto-end trainable pipeline that takes a single satellite image
and generates a geometrically consistent panoramic RGB
image. We thus proposed a neural network with a differentiable geo-transformation layer that links a semantically
labeled satellite depth image with a corresponding semantic panoramic street-view depth image which is finally
used for photo-realistic street-view images generation.
The geometric consistency across images significantly
improves the accuracy of the skyline in the panoramic
ground view which is especially important for urban areas.
Our experiments demonstrate that our method outperforms
existing approaches and is able to synthesize more realistic
street-view panoramic images and in larger variability


## Reference
If you use the code, please cite:

    @inproceedings{lu2020geometry,
      title={Geometry-aware satellite-to-ground image synthesis for urban areas},
      author={Lu, Xiaohu and Li, Zuoyue and Cui, Zhaopeng and Oswald, Martin R and Pollefeys, Marc and Qin, Rongjun},
      booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
      pages={859--867},
      year={2020}
    }
