# icp_pairwise
pcl app to stitch two pointclouds based on ICP

Based on this [tutorial](http://pointclouds.org/documentation/tutorials/pairwise_incremental_registration.php#pairwise-incremental-registration) available on PCL's documentation.

currently reads two pcd files, obtains a tranformation estimate and then applies it on the pointcloud.

To do: Port with ROS and then modify initial guess from Eigen identity to tf obtained from robot.
