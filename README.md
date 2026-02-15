# TRPL-VIO
Infrared Inertial Odometry with a Novel Line Feature Strategy
##1.Project Overview
This system is modified based on PL-VINS and improved on our previous work TPL-SLAM. To address the issues of insufficient robustness in pure optical flow methods and poor real-time performance in pure descriptor-based methods, our team proposes a novel infrared inertial odometry system that achieves a balance between robustness and real-time performance. Experimental results validate that the proposed algorithm outperforms both PL-VINS and TPL-SLAM.
###Key Contributions
1）Achieves a good balance between robustness and real-time performance for line feature matching.
2）Fully exploits infrared feature information and constructs the reprojection error from both positional and directional perspectives.
3）Fills the research gap in current SLAM studies for infrared cameras.
##2.Environment Requirements
#Version Requirements
Ubuntu20.04 Opencv4.0. The installation procedure can refer to that of PL-VINS.
