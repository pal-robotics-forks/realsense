^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package realsense2_camera
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1003.3.1 (2022-10-27)
---------------------
* Update version
* 1003.2.3
* Updated changelogs
* Fix compilation in public melodic
* 1003.2.2
* Updated Changelog
* Formating
* Fix empty depth images
* 1003.2.1
* Update Changelog
* 1003.2.0
* Updated Changelog
* Proper way of disabling pal build flags
* Fix dependencies
* Fixing rebase
* Change how disable pal flags are set
* Revert "compatible way of disabling pal flags"
  This reverts commit 4e17d45bb4c8dfb2ac1d7fad3beb481d5e74afd9.
* compatible way of disabling pal flags
* hack to reduce pointcloud publishing frequency
* Changed default value of allow_no_texture_points to true
* added disable_pal_flags() to CMakeLists.txt
* add compilation fixes
* Contributors: Jordan Palacios, Procópio Stein, Sai Kishor Kothakota, Sara Cooper, Victor Lopez, Víctor González, federiconardi, luca, sergiomoyano, victor

1003.2.3 (2022-05-05)
---------------------
* Merge branch 'fix_public_melodic_build' into 'ferrum-devel'
  Fix compilation in public melodic
  See merge request ros-overlays/realsense!27
* Fix compilation in public melodic
* Contributors: Jordan Palacios, luca

1003.2.2 (2021-09-06)
---------------------
* Merge branch 'Fix-empty-depth-images' into 'ferrum-devel'
  Fix empty depth images
  See merge request ros-overlays/realsense!26
* Formating
* Fix empty depth images
* Contributors: sergiomoyano, victor

1003.2.1 (2021-08-27)
---------------------

1003.2.0 (2021-08-24)
---------------------
* Fixing rebase
* Change how disable pal flags are set
* Revert "compatible way of disabling pal flags"
  This reverts commit 4e17d45bb4c8dfb2ac1d7fad3beb481d5e74afd9.
* compatible way of disabling pal flags
* hack to reduce pointcloud publishing frequency
* Changed default value of allow_no_texture_points to true
* added disable_pal_flags() to CMakeLists.txt
* add compilation fixes
* Contributors: Procópio Stein, Sai Kishor Kothakota, Sara Cooper, Victor Lopez, federiconardi, sergiomoyano

1003.3.3 (2022-11-14)
---------------------
* Merge branch 'fix/multiple_cameras_initial_reset' into 'ferrum-devel'
  fix multiple cameras initial_reset issue
  See merge request ros-overlays/realsense!29
* fix multiple cameras initial_reset issue
* Contributors: sergiomoyano

1003.3.2 (2022-11-08)
---------------------
* 1003.3.1
* Update Changelog
* Update version
* 1003.2.3
* Updated changelogs
* Fix compilation in public melodic
* 1003.2.2
* Updated Changelog
* Formating
* Fix empty depth images
* 1003.2.1
* Update Changelog
* 1003.2.0
* Updated Changelog
* Proper way of disabling pal build flags
* Fix dependencies
* Fixing rebase
* Change how disable pal flags are set
* Revert "compatible way of disabling pal flags"
  This reverts commit 4e17d45bb4c8dfb2ac1d7fad3beb481d5e74afd9.
* compatible way of disabling pal flags
* hack to reduce pointcloud publishing frequency
* Changed default value of allow_no_texture_points to true
* added disable_pal_flags() to CMakeLists.txt
* add compilation fixes
* Contributors: Jordan Palacios, Procópio Stein, Sai Kishor Kothakota, Sara Cooper, Victor Lopez, Víctor González, federiconardi, luca, sergiomoyano, victor

2.3.2 (2021-11-15)
------------------
* publish metadata
* Add service: device_info
* add wait_for_device_timeout parameter
* Add reconnect_timeout parameter
* show warning when requested profile cannot be selected.
* send only 4 distortion coeffs when using equidistant
* fixed missing std namespace
* Removing spaces when iterating filters
* Contributors: Collin Avidano, Gintaras, Jacco van der Spek, doronhi

2.3.1 (2021-07-01)
------------------
* add respawn option
* add udev rules to debian installation
* Add support for L535
* Fix occasional missing diagnostic messages
* Contributors: Alex Fernandes Neves, doronhi

2.3.0 (2021-05-05)
------------------
* Fix pointcloud message size when no texture is added.
* Added filling correct Tx, Ty values in projection matrix of right camera.
* Fixed frame_id of right sensor to match left sensor in a stereo pair.pair
* Contributors: Pavlo Kolomiiets, doronhi

2.2.24 (2021-04-21)
-------------------
* Enabling pointcloud while align_depth is set to true creates a pointcloud aligned to color image.
* Removed option to align depth to other streams other then color.
* Contributors: doronhi

2.2.23 (2021-03-24)
-------------------
* Remove the following tests for known playback issue with librealsense2 version 2.43.0: points_cloud_1, align_depth_color_1, align_depth_ir1_1, align_depth_ir1_decimation_1.
* Add filter: HDR_merge
* add default values to infra stream in rs_camera.launch as non are defined in librealsense2.
* fix bug: selection of profile disregarded stream index.
* fix initialization of colorizer inner image
* Contributors: doronhi

2.2.22 (2021-02-18)
-------------------
* Add reset service.
* fix timestamp domain issues
  - Add offset to ros_time only if device uses hardware-clock. Otherwise use device time - either system_time or global_time.
  - Warn of a hardware timestamp possible loop.
* Choose the default profile in case of an invalid request.
* Avoid aligning confidence image.
* Add an option for an Ordered PointCloud.
* Contributors: Isaac I.Y. Saito, Itamar Eliakim, Marc Alban, doronhi

2.2.21 (2020-12-31)
-------------------
* Publish depth confidence image for supporting devices (L515)
* fix reading json file with device other than D400 series.
* remove (temporarily) flaky IMU unit-test.
* Contributors: Isaac I.Y. Saito, doronhi

2.2.20 (2020-11-19)
-------------------
* Add Support - Noetic
* Add demo for using intrinsics from camera_info (show_center_depth.py).
* Add launch option: send logs to ros log file.
* Add feature: get rgb stream from infrared sensor (applies to D415)
* Add feature: Add notification if connected using USB2.1 port.
* Fix bug: Avoid z16h format
* Fix bug: monitor streams frequency without subsribing.
* Fix bug: extrinsincs for right stereo camera refers to the left stereo camera.
* Contributors: Abhijit Majumdar, Isaac I. Y. Saito, Jakub, M-frctrl, Thomas Jespersen, doronhi

2.2.18 (2020-10-26)
-------------------
* Fix bug: Remove parameter with invalid value.
* Fix bug: Colorize the aligned depth image.
* Fix bug: Added pointcloud attributes, when RS2_STREAM_ANY is enabled
* Add feature: enable/disable all sensors. Known issues: parameters persistency and not full power drop.

2.2.17 (2020-09-09)
-------------------
* Fix for ROS on Windows
* Contributors: Lou Amadio, doronhi

2.2.16 (2020-08-06)
-------------------
* Add PID to support D455.
* Improve instability of dynamic reconfigurable options.
* rs_camera.lauch: add "enable_infra" for L515 support.
* Contributors: doronhi

2.2.15 (2020-07-13)
-------------------
* Check runtime version of librealsense2 vs. compiled version and issue a warning is mismatch occurs.
* Support both L515 and L515 pre-prq versions.
* set infra, fisheye, IMU and pose streams to be false by default.
* add d435i-xacro
* comply to ROS Noetic xacro rules (backcompatible with ROS Melodic) 
* Contributors: Marco Camurri, doronhi

2.2.14 (2020-06-18)
-------------------
* Fix compatibility with Librealsense2 Version 2.35.2.
* Fix support for L515.
* Fix urdf issues.
* Add noetic support: change state_publisher into robot_state_publisher
* fix distortion correction model for T265 (equidistant)
* fix stability issues. Stop sensors at program termination.
* Contributors: Brice, Helen Oleynikova, doronhi

* upgrade version to 2.2.13
* fix ctrl-C closing issues.
* handle device creation exceptions.
* support LiDAR camera L515.
* optimize pointcloud. Contributors: Davide Faconti
* fix usb port id parsing issues.
* Add eigen dependency - missing for Melodic. Contributors: Antoine Hoarau
