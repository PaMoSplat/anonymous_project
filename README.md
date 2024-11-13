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




## Poster
 <p align="center" style="text-align: center;">
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/images/poster.png" alt="PaMoSplat Logo" style="vertical-align: bottom; width:1000px;"/>
</p>


## Abstract

Dynamic scene reconstruction is a critical yet challenging task at the intersection of robotics and computer vision. 
Despite recent advancements in 3D Gaussian Splatting (3DGS) based approaches for modeling dynamics, achieving high-quality rendering and precise tracking in scenes characterized by large, complex motions remains formidable.
To address these challenges, we propose PaMoSplat, a novel Gaussian splatting framework incorporating part awareness and motion priors. 
Two key insights are: 1) Parts serve as primitives for scene deformation, and 2) Motion cues from optical flow can effectively guide part motion.
In PaMoSplat, for the initial timestamp, the graph clustering technique facilitates the lifting of multi-view segmentation masks into 3D to create Gaussian parts. For subsequent timestamps, a differential evolutionary algorithm is employed to infer the prior motion of these Gaussian parts based on the optical flow across views, serving as a warm-start state for further optimization. Additionally, PaMoSplat introduces internal learnable rigidity for the parts and flow-supervised rendering loss.
Experiments conducted on various scenes, including real-world setups, have demonstrated that PaMoSplat achieves excellent rendering quality and tracking accuracy. Furthermore, it enables part-level downstream applications, such as 4D scene editing for enhancing robot training data.
 

## Results

### Gaussian Centers + Track Trajectories


 <p align="center" style="text-align: center;">
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/basketball_center.gif" alt="basketball_center.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/box_center.gif" alt="box_center.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/football_center.gif" alt="football_center.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/juggle_center.gif" alt="juggle_center.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/softball_center.gif" alt="softball_center.gif" style="vertical-align: bottom; width:195px;"/>
</p>

 <p align="center" style="text-align: center;">
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/tennis_center.gif" alt="tennis_color.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/robot_task_center.gif" alt="robot_task_color.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/pendulums_center.gif" alt="pendulums_color.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/spongebowl_center.gif" alt="spongebowl_color.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/clothpan_center.gif" alt="clothpan_color.gif" style="vertical-align: bottom; width:195px;"/>
</p>


### Colors + Track Trajectories

 <p align="center" style="text-align: center;">
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/basketball_color.gif" alt="basketball_color.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/box_color.gif" alt="box_color.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/football_color.gif" alt="football_color.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/juggle_color.gif" alt="juggle_color.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/softball_color.gif" alt="softball_color.gif" style="vertical-align: bottom; width:195px;"/>
</p>

 <p align="center" style="text-align: center;">
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/tennis_color.gif" alt="tennis_color.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/robot_task_color.gif" alt="robot_task_color.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/pendulums_color.gif" alt="pendulums_color.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/spongebowl_color.gif" alt="spongebowl_color.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/clothpan_color.gif" alt="clothpan_color.gif" style="vertical-align: bottom; width:195px;"/>
</p>


### Part + Track Trajectories

 <p align="center" style="text-align: center;">
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/basketball_part.gif" alt="basketball_part.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/box_part.gif" alt="box_part.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/football_part.gif" alt="football_part.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/juggle_part.gif" alt="juggle_part.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/softball_part.gif" alt="softball_part.gif" style="vertical-align: bottom; width:195px;"/>
</p>

 <p align="center" style="text-align: center;">
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/tennis_part.gif" alt="tennis_part.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/robot_task_part.gif" alt="robot_task_part.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/pendulums_part.gif" alt="pendulums_part.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/spongebowl_part.gif" alt="spongebowl_part.gif" style="vertical-align: bottom; width:195px;"/>
  <img src="https://github.com/PaMoSplat/anonymous_project/blob/main/gif/clothpan_part.gif" alt="clothpan_part.gif" style="vertical-align: bottom; width:195px;"/>
</p>



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
