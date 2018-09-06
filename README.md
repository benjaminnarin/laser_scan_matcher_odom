Laser scan tools for ROS
===================================

Overview
-----------------------------------

Note : Modified Version from ccny-ros-pkg/scan_tools

Note : Modifications Taken From https://answers.ros.org/question/12489/obtaining-nav_msgsodometry-from-a-laser_scan-eg-with-laser_scan_matcher/

Laser scan processing tools. The meta-package contains:

 * `laser_scan_matcher`: an incremental laser scan matcher, using Andrea Censi's Canonical
Scan Matcher implementation. It downloads and installs Andrea Censi's Canonical Scan Matcher [1] locally.

Installing
-----------------------------------

### From source ###

Goto your workspace directory for rosbuild.

Make sure you have git installed:

    sudo apt-get install git-core

Download the package from our repository:

    git clone https://github.com/usiraj/laser_scan_matcher.git


Compile the package from its folder:

    make

More info for orignal package
-----------------------------------

http://wiki.ros.org/scan_tools

References
-----------------------------------
 [1] A. Censi, "An ICP variant using a point-to-line metric" Proceedings of the
IEEE International Conference on Robotics and Automation (ICRA), 2008
