# MAV6D

This is the repository for the paper "MAV6D: Keypoint-Guided Efficient 6D Pose Estimation of Micro Aerial Vehicles with Monocular Vision".

The link to the dataset present in the paper: https://westlakeu-my.sharepoint.com/:f:/g/personal/zhao_lab_westlake_edu_cn/EkrnS8qa6tpLmjUKE5xJ6FkBAfm9NWby8nL5blPgPBdTCQ?e=d3bSdT.

This dataset includes RGB images, labels of different formats, and mask images.

Label format in directory "/label": timestamp_camera t_x t_y t_z r_x r_y r_z r_w timestamp_uav t_x t_y t_z r_x r_y r_z r_w. 
The 6D pose is written as the 3D position (t_x, t_y, t_z) and 3D rotation in quaternion (r_x, r_y, r_z, r_w ).

In addition, we also provide a python code for changing the dataset to other formats, such as .json and .yml. 
The main parameters of the camera and MAV are included in this code.

If you have any problem when using this dataset, please feel free to contact: zhengye@westlake.edu.cn.
