# SLAM 相关论文阅读笔记

这个 Repo 主要用来整理自己读过的 SLAM 相关的论文以及比较感兴趣准备阅读的论文，大部分都会写一份博客对阅读过程进行整理。如果论文附有开源代码会视情况学习一下源码。

## LO (Lidar Odometry)

### Feature-Based

- [LOAM: Lidar Odometry and Mapping in Real-time](https://www.ri.cmu.edu/pub_files/2014/7/Ji_LidarMapping_RSS2014_v8.pdf) [[阅读笔记](https://xiaotaoguo.com/p/paper-note-loam/)] [[ALOAM 原 Repo](https://github.com/HKUST-Aerial-Robotics/A-LOAM)] [[ALOAM 代码注释](https://github.com/XiaotaoGuo/a-loam-w-comment)]
- [LeGO-LOAM: Lightweight and Ground-Optimized Lidar Odometry and Mapping on Variable Terrain](https://github.com/RobustFieldAutonomyLab/LeGO-LOAM/blob/master/Shan_Englot_IROS_2018_Preprint.pdf)[[原 Repo](https://github.com/RobustFieldAutonomyLab/LeGO-LOAM)] [[代码整理](https://github.com/XiaotaoGuo/lego-loam-w-comments)]

## LIO (Lidar Inertial Odometry)

### Optimization-Based

- [LIO-SAM: Tightly-coupled Lidar Inertial Odometry via Smoothing and Mapping](https://arxiv.org/pdf/2007.00258.pdf) [[阅读笔记](https://www.xiaotaoguo.com/p/paper-note-lio-sam/)][[原 Repo](https://github.com/TixiaoShan/LIO-SAM)][[代码注释](https://github.com/XiaotaoGuo/lio-sam-w-comments)]

### Kalman Filter-Based

- [LINS: A Lidar-Inertial State Estimator for Robust and Efficient Navigation](https://arxiv.org/pdf/1907.02233.pdf) [[阅读笔记](https://xiaotaoguo.com/p/paper-note-lins/)]] [[原 Repo](https://github.com/ChaoqinRobotics/LINS---LiDAR-inertial-SLAM)][代码整理-TODO]

## Lidar Loop Clousure

- [Real-Time Loop Closure in 2D LIDAR SLAM](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/45466.pdf) [[阅读笔记](https://xiaotaoguo.com/p/paper-note-real-time-loop-closure-2d-lidar-slam/)]
- [Scan Context: Egocentric Spatial Descriptor for Place Recognition within 3D Point Cloud Map](https://ieeexplore.ieee.org/document/8593953) [[阅读笔记](https://www.xiaotaoguo.com/p/paper-note-scan-context/)][[SC-LeGO-LOAM 代码注释](https://github.com/XiaotaoGuo/SC-LeGO-LOAM)]

## Lifelong Mapping and Localization

- [LiDAR Inertial Odometry Aided Robust LiDAR Localization System in Changing City Scenes](https://songshiyu01.github.io/pdf/LIO_W.Ding_S.Song_ICRA2020.pdf) [[阅读笔记](https://xiaotaoguo.com/p/paper-note-lidarinertialodometryaidedrobustlidarlocalizationsysteminchangingcityscenes/)]
- [Robust and Precise Vehicle Localization based on Multi-sensor Fusion in Diverse City Scenes](https://songshiyu01.github.io/pdf/ICRA18_0470_FI.pdf) [[阅读笔记](https://xiaotaoguo.com/p/paper-note-robust-and-precise-vehicle-localization-based-on-multi-sensor-fusion-in-diverse-city-scenes/)]
- [Long-term map maintenance pipeline for autonomous vehicles](https://arxiv.org/pdf/2008.12449.pdf)[[阅读笔记](https://xiaotaoguo.com/p/paper-notes-long-term-map-maintenance-pipeline-for-autonomous-vehicles/)]
- [A General Framework for Lifelong Localization and Mapping in Changing Environment](https://arxiv.org/pdf/2111.10946.pdf)
- [How to Keep Hd Maps for Automated Driving Up to Date](https://ieeexplore.ieee.org/document/9197419)[[阅读笔记](https://xiaotaoguo.com/p/paper-note-how-to-keep-hd-maps-for-automated-driving-up-to-date/)]

## Optimization

- [The GraphSLAM Algorithm with Applications to Large-Scale Mapping of Urban Structures](http://robots.stanford.edu/papers/thrun.graphslam.pdf) [[阅读笔记](https://xiaotaoguo.com/tags/the-graphslam-algorithm-with-applications-to-large-scale-mapping-of-urban-structures/)]
