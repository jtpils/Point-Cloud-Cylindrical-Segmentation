# Point-Cloud-Cylindrical-Segmentation

Point cloud segmentation for cylindrical objects using point cloud library.

The algorithm is:
1) Filter outliers
2) Estimate surface normal
3) Implement RANSAC method to obtain cylindrical coefficients with distance threshold of 5cm with respect to inliers.

References:
PCL Documentation: http://pointclouds.org/documentation/tutorials/cylinder_segmentation.php
Installation of PCL-Python: https://github.com/Sirokujira/pcl-conda-recipes
