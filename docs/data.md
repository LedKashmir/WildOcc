**1. Download Rellis-3D full dataset data [HERE]([https://www.nuscenes.org/download](https://pan.baidu.com/s/1akqSm7mpIMyUJhn_qwg3-w?pwd=4gk3)). Folder structure:**
```
WildOcc_V2.0
├── data/
│   ├── Rellis-3D/
│   │   ├── 00000/
│   │   ├── pylon_camera_node
│   │   ├── os1_cloud_node_kitti_bin
│   │   ├── transforms.yaml
│   │   ├── vel2os1.yaml
│   │   ├── 00001/
│   │   ├── 00002/
│   │   ├── 00003/
│   │   ├── 00004/
```



**2. Download our generated dense occupancy labels (resolution 100x100x40 with voxel size 0.2m) and put and unzip it in data.**
| Resolution | Range | Link | Size |
| :---: | :---: | :---: | :---: |
| 160, 160, 40 | [0, -16, -2, 32, 16, 6] | [link](https://pan.baidu.com/s/1YcvsSItDWVpfQdtHny1OgQ?pwd=2wn9) code: 2wn9| 18.08G |

Please note that: <br/>
1. The shape of each npy file is (n,4), where n is the number of non-empty occupancies. Four dimensions represent xyz and semantic label respectively. <br/>
2. We will release dataset V2.0, which contains more semantic categories and has larger range of perception. <br/>
