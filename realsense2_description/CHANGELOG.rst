^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package realsense2_description
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1003.3.1 (2022-10-27)
---------------------
* Update version
* 1003.2.3
* Updated changelogs
* 1003.2.2
* Updated Changelog
* 1003.2.1
* Update Changelog
* Remove materials file to avoid double definition
* 1003.2.0
* Updated Changelog
* Fixing view model
* Fixing rebase
* Readd topics_ns:=camera  argument
* fixed tests usage of extrinsic param
* updated realsense urdf for ari simulation
* Changed /depth/points to /depth/color/points
* added publish_pointcloud argument to urdf
* Add transform between pose_frame and camera link for image orientation
* Add pose_frame link
* added T265 URDF and gazebo xacro
* added D435 gazebo xacro to use realsense gazebo plugin
* Contributors: Jordan Palacios, Procópio Stein, Sai Kishor Kothakota, Victor Lopez, Víctor González, davidfernandez, federiconardi, saracooper, sergiomoyano

1003.2.3 (2022-05-05)
---------------------

1003.2.2 (2021-09-06)
---------------------

1003.2.1 (2021-08-27)
---------------------
* Merge branch 'use_named_material' into 'ferrum-devel'
  Remove materials file to avoid double definition
  See merge request ros-overlays/realsense!25
* Remove materials file to avoid double definition
* Contributors: davidfernandez, victorgonzalez

1003.2.0 (2021-08-24)
---------------------
* Fixing view model
* Fixing rebase
* Readd topics_ns:=camera  argument
* fixed tests usage of extrinsic param
* updated realsense urdf for ari simulation
* Changed /depth/points to /depth/color/points
* added publish_pointcloud argument to urdf
* Add transform between pose_frame and camera link for image orientation
* Add pose_frame link
* added T265 URDF and gazebo xacro
* added D435 gazebo xacro to use realsense gazebo plugin
* Contributors: Procópio Stein, Sai Kishor Kothakota, Victor Lopez, federiconardi, saracooper, sergiomoyano

1003.3.3 (2022-11-14)
---------------------

1003.3.2 (2022-11-08)
---------------------
* Merge branch 'feat/d455-urdf-gazebo' into 'ferrum-devel'
  Added support for gazebo with d455 and pal changes in d455 urdf
  See merge request ros-overlays/realsense!28
* Added support for gazebo with d455 and pal changes in d455 urdf
* 1003.3.1
* Update Changelog
* Update version
* 1003.2.3
* Updated changelogs
* 1003.2.2
* Updated Changelog
* 1003.2.1
* Update Changelog
* Remove materials file to avoid double definition
* 1003.2.0
* Updated Changelog
* Fixing view model
* Fixing rebase
* Readd topics_ns:=camera  argument
* fixed tests usage of extrinsic param
* updated realsense urdf for ari simulation
* Changed /depth/points to /depth/color/points
* added publish_pointcloud argument to urdf
* Add transform between pose_frame and camera link for image orientation
* Add pose_frame link
* added T265 URDF and gazebo xacro
* added D435 gazebo xacro to use realsense gazebo plugin
* Contributors: Jordan Palacios, Procópio Stein, Sai Kishor Kothakota, Victor Lopez, Víctor González, davidfernandez, federiconardi, saracooper, sergiomoyano

2.3.2 (2021-11-15)
------------------
* Add D455 description
* Add missing aluminum material to d415 model.
* Contributors: Gilad Bretter, doronhi

2.3.1 (2021-07-01)
------------------
* add imu frames to _l515.urdf.xacro
* Contributors: Simon Honigmann, doronhi

2.3.0 (2021-05-05)
------------------

2.2.24 (2021-04-21)
-------------------
* Add conditional param use_mesh.
* Contributors: Teo Cardoso

2.2.23 (2021-03-24)
-------------------

2.2.22 (2021-02-18)
-------------------
* Fix mass of d415
* Consistent add_plug in xacros and launch files
* Contributors: Manuel Stahl, Tim Übelhör, doronhi

2.2.21 (2020-12-31)
-------------------

2.2.20 (2020-11-19)
-------------------
* Add urdf file for l515
* Contributors: doronhi

2.2.18 (2020-10-26)
-------------------
* Feature: Add name to usb_plug to enable multiple copies of usb_plug model.
* Fix mass of d435 - from lgulich
* Contributors: Guillaume, doronhi, lgulich

2.2.17 (2020-09-09)
-------------------

2.2.16 (2020-08-06)
-------------------

2.2.15 (2020-07-13)
-------------------
* Merge remote-tracking branch 'origin/development' into development
* Merge pull request `#1126 <https://github.com/intel-ros/realsense/issues/1126>`_ from mcamurri/add-d435i-xacro
  add D435i modules, urdf and launchfile
* comply to ROS Noetic xacro rules (backcompatible with ROS Melodic)
* Merge branch 'development' into add-d435i-xacro
* Merge branch 'development' of https://github.com/IntelRealSense/realsense-ros into development
  realsense2_description/urdf/test_d435_multiple_cameras.urdf.xacro
* move xml start line in the right place
* add D435i modules, urdf and launchfile
* fix use_nominal_extrinsics arg/property
* add D435i modules, urdf and launchfile
* Contributors: Marco Camurri, doronhi

2.2.14 (2020-06-18)
-------------------
* fix urdf issues (arg use_nominal_extrinsics).
* Add noetic support: 
  - urdf files.
  - change state_publisher into robot_state_publisher
* correct offset between camera_link and base_link
* Contributors: Brice, Marco Camurri, doronhi

* upgrade version to 2.2.13
