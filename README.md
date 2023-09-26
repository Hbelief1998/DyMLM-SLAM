- [DyMLM-SLAM](#dymlm-slam)
  - [1. Introduction](#1-introduction)
  - [2. Video](#2-video)
  - [3. Abstract and Framework](#3-abstract-and-framework)
  - [4. Performance](#4-performance)
    - [Point Cloud Map and Octree Map](#point-cloud-map-and-octree-map)
    - [Plane Map](#plane-map)
    - [Object Map](#object-map)
    - [Robustness Test in Real Environment](#robustness-test-in-real-environment)
    - [Dynamic Object Tracking Experiment](#dynamic-object-tracking-experiment)
  - [3. Future](#3-future)
  - [4. Todo](#4-todo)
  - [5. Contact](#5-contact)

# DyMLM-SLAM

## 1. Introduction

This is the open-source repository for my paper titled **Multi-level Map Construction for Dynamic Scenes**, which is being prepared for submission to ICRA 2024.

[Paper](https://arxiv.org/pdf/2308.04000.pdf)

## 2. Video
[YouTube](https://www.youtube.com/watch?v=MtDlSgATXAo) | [bilibili](https://www.bilibili.com/video/BV1PF411f788/?vd_source=6546448e43097ee53c80bf0d555403f7)

<!-- 摘要和框架 -->
## 3. Abstract and Framework
In dynamic scenes, both localization and mapping in visual SLAM face significant challenges. In recent years, numerous outstanding research works have proposed effective solutions for the localization problem. However, there has been a scarcity of excellent works focusing on constructing long-term consistent maps in dynamic scenes, which severely hampers map applications. To address this issue, we have designed a multi-level map construction system tailored for dynamic scenes. In this system, we employ multi-object tracking algorithms, DBSCAN clustering algorithm, and depth information to rectify the results of object detection, accurately extract static point clouds, and construct dense point cloud maps and octree maps. We propose a plane map construction algorithm specialized for dynamic scenes, involving the extraction, filtering, data association, and fusion optimization of planes in dynamic environments, thus creating a plane map. Additionally, we introduce an object map construction algorithm targeted at dynamic scenes, which includes object parameterization, data association, and update optimization. Extensive experiments on public datasets and real-world scenarios validate the accuracy of the multi-level maps constructed in this study and the robustness of the proposed algorithms. Furthermore, we demonstrate the practical application prospects of our algorithms by utilizing the constructed object maps for dynamic object tracking.  

+ To the best of our knowledge, in dynamic scenes, this paper is the first work to construct plane maps, and also the first to accurately parameterize objects and build accurate and complete lightweight object maps.  

+ Overview
![overview](https://github.com/Hbelief1998/DyMLM-SLAM/blob/master/images/overview.png)

+ Comparison with object map construction of SG-SLAM
![SG-SLAM](https://github.com/Hbelief1998/DyMLM-SLAM/blob/master/images/Compared_with_SGSLAM.png)  
  <!-- + (S. Cheng, C. Sun, S. Zhang and D. Zhang, "SG-SLAM: A Real-Time RGB-D Visual SLAM Toward Dynamic Scenes With Semantic and Geometric Information," in IEEE Transactions on Instrumentation and Measurement, vol. 72, pp. 1-12, 2023, Art no. 7501012, doi: 10.1109/TIM.2022.3228006.) -->

## 4. Performance

### Point Cloud Map and Octree Map
![PCOMap](https://github.com/Hbelief1998/DyMLM-SLAM/blob/master/images/Point%20cloud%20map%20and%20Octree%20map.png)

### Plane Map
![PlaneMap](https://github.com/Hbelief1998/DyMLM-SLAM/blob/master/images/plane%20map.png)

### Object Map
![ObjectMap](https://github.com/Hbelief1998/DyMLM-SLAM/blob/master/images/object%20map.png)  

### Robustness Test in Real Environment
![RealSense](https://github.com/Hbelief1998/DyMLM-SLAM/blob/master/images/real%20sense.png)

### Dynamic Object Tracking Experiment
![DyObjTrack](https://github.com/Hbelief1998/DyMLM-SLAM/blob/master/images/DyObjTrack.png)


## 3. Future

We will open source the **basic version of our code** as soon as possible.

## 4. Todo

- [x] Receive ICRA publication notice
- [ ] Ready to official publication
- [ ] Show more technical details
- [ ] Ready to open source basic version

## 5. Contact

If you have any suggestion or cooperation intention, you can contact us directly：

- Gmail：hu928702964@gmail.com
- Email：hu928702964@163.com

