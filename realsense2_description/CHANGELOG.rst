^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package realsense2_description
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Forthcoming
-----------
* Merge branch 'tpe/simplify_3d_mesh' into 'alum-devel'
  Fix dae mesh + replace by a simplified mesh for simulation
  See merge request ros-overlays/realsense!42
* Fix origin of inertia matrix
* Fix position + collision + inertia of d435
* Remove material
* Change use mesh to false by default and replace the box by the simplified mesh
* Fix dae mesh + replace by a simplified mesh for simulation
* Contributors: sergiomoyano, thomas.peyrucain

2000.3.0 (2025-01-22)
---------------------
* using topics_ns for d435i
* Contributors: antoniobrandi

2000.2.0 (2025-01-22)
---------------------
* fix d405 macro
* Contributors: andreacapodacqua

2000.1.0 (2024-10-14)
---------------------
* Merge branch 'man/added-d405' into 'alum-devel'
  added meshes and urdf for d405
  See merge request ros-overlays/realsense!37
* added meshes and urdf for d405
* Contributors: martinaannicelli, sergiomoyano

2000.0.4 (2024-02-12)
---------------------
* Merge branch 'fix/ros2-pkg-name' into 'alum-devel'
  fix pkg name of gazebo plugins
  See merge request ros-overlays/realsense!32
* fix pkg name of gazebo plugins
* Contributors: andreacapodacqua, sergiomoyano

2000.0.3 (2024-02-12)
---------------------

2000.0.2 (2024-01-24)
---------------------
* Added realsense gazebo urdf in d435, d455 and l515
* Contributors: sergiomoyano

2000.0.1 (2024-01-19)
---------------------
* Set overlay package version
* Contributors: sergiomoyano

4.54.1 (2023-06-27)
-------------------
* Update mesh path
* clone PR1637 to ros2-development
* Fix Apache License Header and Intel Copyrights
* apply copyrights and license on project
* Replace deprecated parameter node_name with name
* Contributors: Arun Prasad, Nir Azkiel, SamerKhshiboun, augustelalande, marqrazz

4.51.1 (2022-09-13)
-------------------
* Add copyright and license to all ROS2-beta source files

* Contributors: SamerKhshiboun

4.0.4 (2022-03-20)
------------------

4.0.3 (2022-03-16)
------------------

4.0.2 (2022-02-24)
------------------

4.0.1 (2022-02-01)
------------------
* Add D455 urdf files

* Contributors: nomumu, JamesChooWK, doronhi

3.1.3 (2020-12-28)
------------------
* fix realsense2_description's dependency to realsense2_camera_msgs
  remove boost dependency.
  rename node_namespace to namespace
  rename node_executable to executable
* Contributors: benlev, Gilaadb, doronhi

3.1.2 (2020-12-10)
------------------
* Add urdf for L515.
* remove librealsense2 and realsense2_camera dependencies
* Add models for D415, D435, D435i.
  For visualization, can be presented using view_model.launch.py
* fix view_d435_model.launch.py and view_d435i_model.launch.py
  run: ros2 launch realsense2_description view_d435i_model.launch.py
* Contributors: Ryan Shim, doronhi

2.2.14 (2020-06-18)
-------------------
* fix urdf issues (arg use_nominal_extrinsics).
* Add noetic support: 
  - urdf files.
  - change state_publisher into robot_state_publisher
* correct offset between camera_link and base_link
* Contributors: Brice, Marco Camurri, doronhi

* upgrade version to 2.2.13
