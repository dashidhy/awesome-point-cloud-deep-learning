# Awesome papers of deep learning on point clouds

This repo collects papers on point cloud deep learning. Note that the stars I give to each paper contain personal bias for my own project, but actually I do appreciate all the works that have been done in this area. For my own purpose, I can't include all the papers that have been published. A more complete paper list since 2017 is here: [https://github.com/Yochengliu/awesome-point-cloud-analysis](https://github.com/Yochengliu/awesome-point-cloud-analysis).

## 1. Feature extractor

- **Escape from Cells: Deep Kd-Networks for the Recognition of 3D Point Cloud Models** (ICCV 2017), R. Klokov et al. [[pdf]](https://arxiv.org/pdf/1704.01222.pdf) :star: :star: :star: :star:
- **PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation** (CVPR 2017), C. R. Qi et al. [[pdf]](https://arxiv.org/pdf/1612.00593.pdf) [[Github]](https://github.com/charlesq34/pointnet) :star: :star: :star: :star: :star:
- **PointNet++: Deep Hierarchical Feature Learning on Point Sets in a Metric Space** (NeurIPS 2017), C. R. Qi et al. [[pdf]](https://arxiv.org/pdf/1706.02413.pdf) [[Github]](https://github.com/charlesq34/pointnet2) :star: :star: :star: :star: :star:
- **PointCNN: Convolution On X-Transformed Points** (NeurIPS 2018) Y. Li et al, [[pdf]](https://arxiv.org/pdf/1801.07791.pdf) [[Github]](https://github.com/yangyanli/PointCNN) :star: :star: :star:
- **A-CNN: Annularly Convolutional Neural Networks on Point Clouds** (CVPR 2019), A. Komarichev et al. [[pdf]](https://arxiv.org/pdf/1904.08017.pdf) <br/> :star: :star: :star:
- **Relation-Shape Convolutional Neural Network for Point Cloud Analysis** (CVPR 2019), Y. Liu et al. [[pdf]](https://arxiv.org/pdf/1904.07601.pdf) <br/> :star: :star: :star: :star:

### Other useful links

- [ModelNet Benchmark](http://modelnet.cs.princeton.edu/)

## 2. Detection

### Only geometric as input

**Mapping into regular grids**

- **Voting for Voting in Online Point Cloud Object Detection** (RSS 2015), D. Z. Wang et al. [[pdf]](http://www.robots.ox.ac.uk/~mobile/Papers/2015RSS_wang.pdf) :star: :star: :star:
- **Vote3Deep: Fast Object Detection in 3D Point Clouds Using Efficient Convolutional Neural Networks** (ICRA 2017), M. Engelcke et al. [[pdf]](https://arxiv.org/pdf/1609.06666.pdf) :star: :star: :star:
- **3D fully convolutional network for vehicle detection in point cloud** (IROS 2017) B. Li. [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8205955) [[Github]](https://github.com/yukitsuji/3D_CNN_tensorflow) :star: :star: :star:
- **VoxelNet: End-to-End Learning for Point Cloud Based 3D Object Detection** (CVPR 2018), Y. Zhou et al. [[pdf]](https://arxiv.org/pdf/1711.06396.pdf) <br/> :star: :star: :star: :star: :star:
- **PIXOR: Real-time 3D Object Detection From Point Clouds** (CVPR 2018), B. Yang et al. [[pdf]](https://arxiv.org/pdf/1902.06326.pdf) :star: :star: :star: :star:
- **SECOND: Sparsely Embedded Convolutional Detection** (Sensors 2018) Y. Yan et al. [[pdf]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6210968/pdf/sensors-18-03337.pdf) [[Github]](https://github.com/traveller59/second.pytorch) :star: :star: :star:
- **PointPillars: Fast Encoders for Object Detection from Point Clouds** (CVPR 2019), A. Lang et al. [[pdf]](https://arxiv.org/pdf/1812.05784.pdf) [[GIthub]](https://github.com/nutonomy/second.pytorch)  <br/> :star: :star: :star: :star: :star:
- **Part-A^2 Net: 3D Part-Aware and Aggregation Neural Network for Object Detection from Point Cloud** (ArXiv 2019) S. Shi et al. [[pdf]](https://arxiv.org/pdf/1907.03670.pdf) :star: :star: :star: :star: :star:

**Directly operate on point clouds**

- **PointRCNN: 3D Object Proposal Generation and Detection from Point Cloud** (CVPR 2019), S. Shi et al. [[pdf]](https://arxiv.org/pdf/1812.04244.pdf) [[Github]](https://github.com/sshaoshuai/PointRCNN) :star: :star: :star: :star: :star:
- **Deep Hough Voting for 3D Object Detection in Point Clouds** (ArXiv 2019) C. R. Qi et al. [[pdf]](https://arxiv.org/pdf/1904.09664.pdf) :star: :star: :star: :star: :star:

### 2D proposal based

- **IPOD: Intensive Point-based Object Detector for Point Cloud** (ArXiv 2018) Z. Yang et al. [[pdf]](https://arxiv.org/pdf/1812.05276.pdf) :star: :star: :star: :star:
- **RoarNet: A Robust 3D Object Detection based on RegiOn Approximation Refinement** ((ArXiv 2018), K. Shin et al. [[pdf]](https://arxiv.org/pdf/1811.03818.pdf)
- **Frustum PointNets for 3D Object Detection from RGB-D Data** (CVPR 2018), C. R. Qi et al. [[pdf]](https://arxiv.org/pdf/1711.08488.pdf) [[GIthub]](https://github.com/charlesq34/frustum-pointnets) <br/> :star: :star: :star: :star: :star:
- **Frustum ConvNet: Sliding Frustums to Aggregate Local Point-Wise Features for Amodal 3D Object Detection** (CVPR 2019), Z. Wang et al. [[pdf]](https://arxiv.org/pdf/1903.01864.pdf) :star: :star: :star:

### Multi-view/multi-sensor/multi-task

- **Multi-View 3D Object Detection Network for Autonomous Driving** (CVPR 2017), X. Chen et al. [[pdf]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Chen_Multi-View_3D_Object_CVPR_2017_paper.pdf) [[Github]](https://github.com/bostondiditeam/MV3D) <br/> :star: :star: :star: :star:
- **PointFusion: Deep Sensor Fusion for 3D Bounding Box Estimation** (CVPR 2018), D. Xu et al. [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Xu_PointFusion_Deep_Sensor_CVPR_2018_paper.pdf) :star: :star: :star: :star:
- **Deep Continuous Fusion for Multi-Sensor 3D Object Detection** (ECCV 2018), M. Liang et al. [[pdf]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Ming_Liang_Deep_Continuous_Fusion_ECCV_2018_paper.pdf) :star: :star: :star: :star:
- **Multi-Task Multi-Sensor Fusion for 3D Object Detection** (CVPR 2019), M. Liang et al. [[pdf]](http://www.cs.toronto.edu/~byang/papers/mmf.pdf) :star: :star: :star: :star: :star:
- **MVX-Net: Multimodal VoxelNet for 3D Object Detection** (ICRA 2019), V. A. Sindagi et al. [[pdf]](https://arxiv.org/pdf/1904.01649.pdf) :star: :star: :star: :star:

### Other useful links
- [KITTI Leaderboard](http://www.cvlibs.net/datasets/kitti/eval_object.php?obj_benchmark=3d)
- [nuScenes Leaderboard](https://www.nuscenes.org/object-detection?externalData=all&mapData=all&modalities=Any)

## 3. Segmentation

- **Recurrent Slice Networks for 3D Segmentation of Point Clouds** (CVPR 2018), Q. Huang et al. [[pdf]](https://arxiv.org/pdf/1802.04402.pdf) [[Github]](https://github.com/qianguih/RSNet) <br/> :star: :star: :star: :star:
- **SGPN: Similarity Group Proposal Network for 3D Point Cloud Instance Segmentation** (CVPR 2018), W. Wang et al. [[pdf]](https://arxiv.org/pdf/1711.08588.pdf) [[Github]](https://github.com/laughtervv/SGPN) :star: :star: :star: :star:
- **Associatively Segmenting Instances and Semantics in Point Clouds** (CVPR 2019), X. Long et al. [[pdf]](https://arxiv.org/pdf/1902.09852.pdf) <br/> :star: :star: :star: :star: :star:

...(To be completed)

## 4. Dataset

Note that some of these datasets don't provide point cloud data, which means you need some toolboxes to convert data from mesh or RGB-D images.

### Shape understanding

- **ModelNet** [[pdf]](https://people.csail.mit.edu/khosla/papers/cvpr2015_wu.pdf) [[Project]](http://modelnet.cs.princeton.edu/)
- **ShapeNet** [[pdf]](http://shapenet.cs.stanford.edu/shapenet/obj-zip/ShapeNetCore.v2-old/shapenet/tex/TechnicalReport/main.pdf) [[Project]](https://www.shapenet.org/)

### Indoor scenes

- **2D-3D-S** [[pdf]](http://buildingparser.stanford.edu/images/2D-3D-S_2017.pdf) [[Project]](http://buildingparser.stanford.edu/dataset.html)
- **ScanNet** [[pdf]](https://arxiv.org/pdf/1702.04405.pdf) [[Project]](http://www.scan-net.org/)
- **SUN RGB-D** [[pdf]](http://rgbd.cs.princeton.edu/paper.pdf) [[Project]](http://rgbd.cs.princeton.edu/)

### Autonomous driving (Lidar point cloud)

- **KITTI** [[pdf]](http://www.cvlibs.net/publications/Geiger2013IJRR.pdf) [[Project]](http://www.cvlibs.net/datasets/kitti/eval_object.php?obj_benchmark=3d)
- **nuScenes** [[pdf]](https://arxiv.org/pdf/1903.11027.pdf) [[Project]](https://www.nuscenes.org/)
- **Waymo Open dataset** [[Project]](https://waymo.com/open/)