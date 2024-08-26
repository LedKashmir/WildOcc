# WildOcc: A Dataset and Benchmark for Off-Road 3D Semantic Occupancy Prediction
# Abstract
We establish a benchmark derived from the Rellis-3D dataset, to our knowledge, which is the first off-road 3D occupancy prediction dataset. To achieve accurate dense occupancy ground truth of off-road environment, we optimize the ground truth generate pipeline. Especially, in order to ease adhesion between close objects, we utilize Poisson Reconstruction with different depths on ground(grass) and non-ground(bush, tree) objects separately, instead of the whole scene. In addition, we propose a novel multi-modal LiDAR-camera framework WildOcc, which utilizes pose and temporal information of multi-frame to fuse voxel features from LiDAR and camera. We also propose a knowledge distillation strategy to transfer LiDAR's rich geometry information to context-rich image features.
# Getting Started
 * [Installation](https://github.com/JeffWang987/OpenOccupancy)
 * [Prepare Dataset](https://github.com/LedKashmir/WildOcc/blob/main/docs/data.md)
 * [Train and eval](https://github.com/HuangJunJie2017/BEVDet)
# Acknowledgement
This project is developed based on the following open-sourced projects:
 * [OpenOccupancy](https://github.com/JeffWang987/OpenOccupancy)
 * [SurroundOcc](https://github.com/weiyithu/SurroundOcc)
 * [BEVDet](https://github.com/HuangJunJie2017/BEVDet)

Many thanks for their excellent work.
