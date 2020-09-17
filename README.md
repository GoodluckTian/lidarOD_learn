# 激光雷达资料（obstacle detection and fusion）

#### 基础知识
PCL、ROS、CMake、opencv、DP

#### IDE
Qtcreator VScode（ros插件）

#### PCL
编译pcl问题较多，参考网上教程和解决方法。省事也可直接sudo apt-get install  
pcl官方教程[https://pcl.readthedocs.io/projects/tutorials/en/latest/](https://pcl.readthedocs.io/projects/tutorials/en/latest/)   
自己的一些代码[https://gitee.com/leox24/pcl_example.git](https://gitee.com/leox24/pcl_example.git)


#### ROS
sudo apt-get install 直接安装  
官方教程[http://wiki.ros.org/](http://wiki.ros.org/)  
百度云视频：https://pan.baidu.com/s/1kVPTRMGa4E7SUwVCp1YsjA  提取码:4c0r  

#### 教程/代码

优达 od fusion track 百度云视频：https://pan.baidu.com/s/11Mfx50MR8H6Xce7UBZFG5g 提取码:5rb8  
传统激光雷达聚类-ros [https://gitee.com/leox24/lidarCluster.git](https://gitee.com/leox24/lidarCluster.git)  
lidar+camera融合检测-ros [https://gitee.com/leox24/lidarimg_ws.git](https://gitee.com/leox24/lidarimg_ws.git)  

#### KITTI

传统激光雷达检测算法已淘汰，建议上深度学习检测。  
kitti数据集中obstacle的3D检测 有部分开源代码和论文，建议阅读，需要深度学习基础  
kitti要梯子  

检测之外还有跟踪可以做，跟踪包括关联匹配、航迹更新等，可以参考Apollo思路。  

Apollo检测源码也可学习，github上有。  