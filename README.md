# DyMLM-SLAM

## 1. Introduction

This is the open-source repository for my paper titled **Multi-level Map Construction for Dynamic Scenes**, which is being prepared for submission to ICRA 2024.

<!-- 摘要和框架 -->
## 2. Abstract and Framework
In dynamic scenes, both localization and mapping in visual SLAM face significant challenges. In recent years, numerous outstanding research works have proposed effective solutions for the localization problem. However, there has been a scarcity of excellent works focusing on constructing long-term consistent maps in dynamic scenes, which severely hampers map applications. To address this issue, we have designed a multi-level map construction system tailored for dynamic scenes. In this system, we employ multi-object tracking algorithms, DBSCAN clustering algorithm, and depth information to rectify the results of object detection, accurately extract static point clouds, and construct dense point cloud maps and octree maps. We propose a plane map construction algorithm specialized for dynamic scenes, involving the extraction, filtering, data association, and fusion optimization of planes in dynamic environments, thus creating a plane map. Additionally, we introduce an object map construction algorithm targeted at dynamic scenes, which includes object parameterization, data association, and update optimization. Extensive experiments on public datasets and real-world scenarios validate the accuracy of the multi-level maps constructed in this study and the robustness of the proposed algorithms. Furthermore, we demonstrate the practical application prospects of our algorithms by utilizing the constructed object maps for dynamic object tracking.  
![overview.png]()

## 3. Performance
### Video
[YouTube](https://www.youtube.com/watch?v=MtDlSgATXAo) | [bilibili](https://www.bilibili.com/video/BV1PF411f788/?vd_source=6546448e43097ee53c80bf0d555403f7)

### Point cloud map and Octree map



## 2. Performance

- Here is the primary performance of our Efficient  Quadric  Initialization (EQI) algorithm:

![perfomance](https://github.com/caobugai12138/Object-Aware-SLAM/blob/main/images/performance.png?raw=true)

- Here is the primary performance of our Joint  Data  Association (JDA) algorithm:

![](https://github.com/caobugai12138/Object-Aware-SLAM/blob/main/images/DataAssociation.png?raw=true)

- Here is the youtube link of the overview and  performance of our system:

  [Overview of Our System](https://www.youtube.com/watch?v=XDuv2BG_K9Y)

  [Performance of Our System](https://youtu.be/Ng6E-lpqJ6E)

## 3. Future

We will open source the **basic version of our code** as soon as possible.

## 4. Todo

- [x] Receive RA-L publication notice
- [x] Receive IROS publication notice
- [ ] Ready to official publication
- [ ] Show more technical details
- [ ] Ready to open source basic version

## 5. Contact

If you have any suggestion or cooperation intention, you can contact us directly：

- Gmail：caobugai12138@gmail.com
- Email： 3322121807@qq.com

