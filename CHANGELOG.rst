^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package gpd
^^^^^^^^^^^^^^^^^^^^^^^^^

1.0.4 (2019-01-17)
------------------
* Fix missing dependency
* Contributors: Victor Lopez

1.0.3 (2018-12-21)
------------------
* added missing library install rule
* Contributors: Sai Kishor Kothakota

1.0.2 (2018-12-21)
------------------
* added missing install rules
* Contributors: Sai Kishor Kothakota

1.0.1 (2018-12-20)
------------------
* fixing some missing dependencies
* added gpg dependency
* exporting gpd libraries
* added table height setup method
* fixing headers in the files
* fix filepath issue
* screenshot added
* screenshot added
* remove Caffe text from readme
* Merge branch 'forward' of https://github.com/atenpas/gpd into forward
* Reorganize code. Add grasp detection ROS service.
* Update journal reference. Remove deprecated caffe files.
* fix rviz visualization.
* select highest scoring grasps, then cluster; instead of thresholding on the CNN scores
* fix wrong dense layer input size
* update readme
* directory cleanup
* Works without caffe.
* update image in readme for tutorial 0
* change arrow colors of hand frame in tutorial 2's image
* Remove deprecated headers. Update visualization.
* Merge pull request #12 from 2scholz/clustered_grasps_header_fix
  Use PointCloud2 header for clustered_grasps msg
* Merge pull request #16 from tanay-bits/patch-1
  Minor correction of tutorial 2 readme
* Update tutorial_2_grasp_select.md
* parameter explanations workspace, num_samples
* troubleshooting section in readme
* troubleshooting section in readme
* troubleshooting section in readme
* Use PointCloud2 header for clustered_grasps msg
  The time stamp of the PointCloud2 is more useful in this case, because it gives us information
  about the time when the grasps were actually found.
  clustered_grasps' frame_id wasn't set to any value before. Using the header of the PointCloud2
  sets it to the correct value.
* Merge pull request #10 from 2scholz/library_export_fix
  Remove export of grasp_detector library
* Remove export of grasp_detector library
  There is no library named grasp_detector.
* Merge pull request #9 from 2scholz/find_path
  Use find_path to find gpg include path
* Use find_path to find gpg include path
  when using an install prefix other than /usr for gpg the include path cannot
  be found. To fix this problem we use find_path.
* fix importance sampling parameters
* fix parameter name, remove deprecated parameter
* documentation update
* documentation update
* reference correction
* arxiv reference to journal preprint
* remove fc layer files
* Ubuntu 16.04 instructions
* Merge branch 'master' of https://github.com/atenpas/gpd
* Ubuntu 16.04 instructions
* dependency on PCL libraries for test
* decrease view angle picture size
* decrease view angle picture size
* decrease view angle picture size
* update readme for views, 15channels
* views in readme
* views in readme
* views in readme
* clean up caffe subfolder, change video link
* parameter to switch Caffe to CPU mode
* parameter to switch Caffe to CPU mode
* change citation link
* dependencies for defining custom messages
* fix links, add visualization of hand frame
* fix links to tutorials
* link to youtube
* move to github
* Update LICENSE.md
* Contributors: 2scholz, Andreas ten Pas, Benjamin Scholz, Matt Corsaro, Sai Kishor Kothakota, Tanay Choudhary, andreas, atenpas, atp, saikishor
