## MRFMap: Online Probabilistic 3D Mapping using Forward Ray Sensor Models

[[Supplementary]](https://github.com/mrfmap/mrfmap.github.io/blob/master/supp.pdf) | [[Paper]](https://arxiv.org/pdf/2006.03512.pdf) | [[Repository]](https://github.com/mrfmap/mrfmap) | [[ROS Package]](https://github.com/mrfmap/mrfmap_ros)

OctoMap 1cm | MRFMap 1cm
------------|------------
<img src="https://raw.githubusercontent.com/mrfmap/mrfmap.github.io/master/figs/hand_comparison/octomap_res_0_01_rot_0_5_trans_0_5.png" width="200"> | <img src="https://raw.githubusercontent.com/mrfmap/mrfmap.github.io/master/figs/hand_comparison/mrfmap_res_0_01_rot_0_5_trans_0_5.png" width="200">


OctoMap 5cm | MRFMap 5cm
------------|------------
<img src="https://raw.githubusercontent.com/mrfmap/mrfmap.github.io/master/figs/chair_comparison/octomap_res_0_05_rot_1_0_trans_1_0noisy.png" width="200"> | <img src="https://raw.githubusercontent.com/mrfmap/mrfmap.github.io/master/figs/chair_comparison/mrfmap_res_0_05_rot_1_0_trans_1_0noisy.png" width="200">


The MRFMap library implements occupancy inference on configurable hierarchical 3D grids given RGB-D depth data and camera poses using forward sensor models and by explicitly ray tracing through the map volume and coupling the depth measurement with all voxels traversed per ray. 

Detailed information about the approach can be found in the paper "MRFMap: Online Probabilistic 3D Mapping using Forward Ray Sensor Models", published in the proceedings of RSS 2020.

The library has been developed on linux and requires CUDA support. It was developed by Kumar Shaurya Shankar while in the [RISLab](https://www.rislab.org/) at The Robotics Institute at Carnegie Mellon University with Prof. Nathan Michael. 

## License
MRFMap is released under the [BSD 3-Clause License](https://choosealicense.com/licenses/bsd-3-clause/)

## Citations
If you use MRFMap in your work, please cite us!
```bibtex
@proceedings{shankar20mrfmap,
  author = {Shankar, Kumar Shaurya and Michael, Nathan},
  title = {MRFMap: Online Probabilistic 3D Mapping using Forward Ray Sensor Models},
  booktitle = {Robotics: Science and Systems},
  year = 2020
}
```
