<div align="center">
  <h1>Keypoint-Guided Efficient Pose Estimation and Domain Adaptation for Micro Aerial Vehicles</h1>

<p align="center">
  <a href="https://ieeexplore.ieee.org/document/10530350">
    <img src="https://img.shields.io/badge/Paper-blue?logo=googledocs&logoColor=white&labelColor=grey&color=blue"></a>
  <a href="https://www.bilibili.com/video/BV1XD421M7t9/?spm_id_from=333.999.0.0&vd_source=0eec9f8ad388935277d70e12aac978ba">
    <img src="https://img.shields.io/badge/Video-blue?logo=bilibili&logoColor=white&labelColor=grey&color=blue"></a>
  <a href="https://www.youtube.com/watch?v=ppTR65gGlgg">
    <img src="https://img.shields.io/badge/Video-blue?logo=youtube&logoColor=white&labelColor=grey&color=blue"></a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg"></a>
</p>
</div>

This is the repository for the paper "Keypoint-Guided Efficient Pose Estimation and Domain Adaptation for Micro Aerial Vehicles".

<div align="center">
    <img src="https://github.com/user-attachments/assets/b3145469-c23a-49f4-8aea-52ab87aad59f"></a>
</div>

The link to the dataset present in the paper: https://westlakeu-my.sharepoint.com/:f:/g/personal/zhao_lab_westlake_edu_cn/EkrnS8qa6tpLmjUKE5xJ6FkBAfm9NWby8nL5blPgPBdTCQ?e=d3bSdT.

This dataset includes RGB images, labels of different formats, and mask images.

Label format in directory "/label": timestamp_camera t_x t_y t_z r_x r_y r_z r_w timestamp_uav t_x t_y t_z r_x r_y r_z r_w. 
The 6D pose is written as the 3D position (t_x, t_y, t_z) and 3D rotation in quaternion (r_x, r_y, r_z, r_w ).

In addition, we also provide a python code for changing the dataset to other formats, such as .json and .yml. 
The main parameters of the camera and MAV are included in this code.

If you have any problem when using this dataset, please feel free to contact: zhengye@westlake.edu.cn.
