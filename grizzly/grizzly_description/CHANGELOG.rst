^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package grizzly_description
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.4.2 (2018-06-22)
------------------
* [grizzly_description] Installed env_run script.
* Contributors: Tony Baltovski

0.4.1 (2018-06-21)
------------------
* Updated urdf (`#21 <https://github.com/g/grizzly/issues/21>`_)
  * Updated urdf to have both sensor arches, all standard sensors, and some non-standard sensors
  * URDF formatting
* Contributors: dniewinski

0.4.0 (2018-06-05)
------------------
* Minor package.xml and CMakeList.txt clean-up.
* Fix vehicle dimensions for roscontrol
* Added urdf files and control config files for base.launch to run. Updated package.xml files and changelogs to match current version.
* Contributors: Michael Hosmar, Mohamed Elshatshat, Tony Baltovski

0.3.2 (2015-11-06)
------------------

0.3.1 (2015-01-09)
------------------
* Find includes in URDF relative to package locations.
* Remove unneeded joint_state_publisher dependency.
* fix imu topic in simulator
* In navigation pkg, rename config and launch files to localization
* set imu frame ID as imu_link
* Contributors: Mike Purvis, Shokoofeh Pourmehr

0.3.0 (2014-12-18)
------------------
* Fix IMU origin.
* Update physical and collision properties
* update position of wheel's joints
* add hector gps contoller
* add hector imu controller
* change joint names. use rear instead of back
* Aesthetic fixes to grizzly URDF.
* Remove vestigial vcg file.
* Contributors: Mike Purvis, Shokoofeh Pourmehr, dash

0.2.0 (2014-02-28)
------------------

0.1.4 (2014-02-27)
------------------

0.1.3 (2014-02-25)
------------------

0.1.2 (2013-12-04)
------------------
* Remove commented reference to husky_wheel stl, as this was confusing Gazebo.

0.1.1 (2013-11-30)
------------------
* Remove attempt to install non-existant launch folder.

0.1.0 (2013-11-28)
------------------
* Initial cut of a grizzly_description suitable for visualization and simulation.
