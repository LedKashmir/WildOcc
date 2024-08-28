# WildOcc: A Dataset and Benchmark for Off-Road 3D Semantic Occupancy Prediction
# Abstract
3D occupancy prediction plays an important role in 3D scene understanding and is an essential component of autonomous driving, the aim of 3D occupancy prediction is to reconstruct semantic and geometry information of surrounding environment. Off-road environment contains various irregular shapes, therefore 3D Occupancy prediction task align well with the condition. However, most of efforts were paid on urban road environments and few methods were specifically designed for off-road 3D occupancy prediction due to the lack of off-road dataset and benchmark. In this paper, we establish a benchmark derived from the Rellis-3D Dataset, to our knowledge, which is the first off-road 3D occupancy prediction dataset. To achieve accurate dense occupancy ground truth of off-road environment, we optimize the ground truth generate pipeline. Especially, in order to ease adhesion between close objects, we utilize Poisson Reconstruction with different depths on ground(grass) and non-ground(bush, tree) objects separately, instead of the whole scene. In addition, we propose a novel multi-modal LiDAR-camera framework WildOcc, which utilizes pose and temporal information of multi-frame to fuse voxel features from LiDAR and camera. We also propose a knowledge distillation strategy to transfer LiDAR's rich geometry information to context-rich image features.
# Getting Started
# Acknowledgement
This project is developed based on the following open-sourced projects:
 * [OpenOccupancy](https://github.com/JeffWang987/OpenOccupancy)
 * [SurroundOcc](https://github.com/weiyithu/SurroundOcc)
 * [BEVDet](https://github.com/HuangJunJie2017/BEVDet)
 * [Lift, Splat, Shoot](https://github.com/nv-tlabs/lift-splat-shoot)

Many thanks for their excellent work.
