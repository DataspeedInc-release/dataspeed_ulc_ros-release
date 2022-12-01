^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package dataspeed_ulc_can
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.0 (2022-11-30)
------------------
* Reconfigure CAN and ROS messages for new ULC capability
* Use setuptools instead of distutils for python
  http://wiki.ros.org/noetic/Migration#Setuptools_instead_of_Distutils
* Increase CMake minimum version to 3.0.2 to avoid warning about CMP0048
  http://wiki.ros.org/noetic/Migration#Increase_required_CMake_version_to_avoid_author_warning
* Contributors: Kevin Hallenbeck, Micho Radovnikovich

0.0.5 (2019-11-06)
------------------
* Updates scale factor on linear accel and decel limit CAN signals
* Adds README to document the ROS node interface
* Contributors: Micho Radovnikovich

0.0.4 (2019-05-15)
------------------
* Install base Python module instead of including it as a script
* Contributors: Micho Radovnikovich

0.0.3 (2018-12-09)
------------------
* Added tcpNoDelay() for subscribers
* Contributors: Kevin Hallenbeck

0.0.2 (2018-12-05)
------------------
* Cleanup and test updates
* Contributors: Kevin Hallenbeck

0.0.1 (2018-11-30)
------------------
* Initial release
* Contributors: Kevin Hallenbeck, Micho Radovnikovich
