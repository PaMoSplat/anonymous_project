<p align="center" style="text-align: center;">
  <img src="https://github.com/PaMoSplat/anonymous_code/blob/main/logo.svg" alt="PaMoSplat Logo" style="vertical-align: bottom; width:300px;"/>
</p>

<p align="center">
  <h1 align="center"><strong>
    Part-Aware Motion-Guided Gaussian Splatting for Dynamic Scene Reconstruction
  </strong>
</p>






<p align="center">
  <a href="https://github.com/PaMoSplat/anonymous_code" target='_blank'>
    <img src="https://img.shields.io/badge/Code-👔-orange?">
  </a> 
</p>


 ##  Poster
 


 ##  Abstract
Dynamic scene reconstruction is a critical yet challenging task at the intersection of robotics and computer vision. 
Despite recent advancements in 3D Gaussian Splatting (3DGS) based approaches for modeling dynamics, achieving high-quality rendering and precise tracking in scenes characterized by large, complex motions remains formidable.
To address these challenges, we propose PaMoSplat, a novel Gaussian splatting framework incorporating part awareness and motion priors. 
Two key insights are: 1) Parts serve as primitives for scene deformation, and 2) Motion cues from optical flow can effectively guide part motion.
In PaMoSplat, for the initial timestamp, the graph clustering technique facilitates the lifting of multi-view segmentation masks into 3D to create Gaussian parts. For subsequent timestamps, a differential evolutionary algorithm is employed to infer the prior motion of these Gaussian parts based on the optical flow across views, serving as a warm-start state for further optimization. Additionally, PaMoSplat introduces internal learnable rigidity for the parts and flow-supervised rendering loss.
Experiments conducted on various scenes, including real-world setups, have demonstrated that PaMoSplat achieves excellent rendering quality and tracking accuracy. Furthermore, it enables part-level downstream applications, such as 4D scene editing for enhancing robot training data.
 

## 🔗 Citation

If you find our work helpful, please cite:

```bibtex
@article{pamosplat,
  title={PaMoSplat: Part-Aware Motion-Guided Gaussian Splatting for Dynamic Scene Reconstruction},
  author={Anonymous Authors},
  journal={CVPR Under Review},
  year={2025}
}
```
