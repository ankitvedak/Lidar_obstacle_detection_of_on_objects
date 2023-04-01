# LIDAR object detection fro on road objects

<img src="media/ObstacleDetectionFPS.gif" width="700" height="400" />
<img src="media/lidar.gif" width="700" height="400" />


**Note** The [[CMakeLists.txt](https://github.com/udacity/SFND_Lidar_Obstacle_Detection/blob/master/CMakeLists.txt)] file provided in this repo can be used locally if you have the same package versions as mentioned above. If you want to run this project locally (outside the Udacity workspace), please follow the steps under the **Local Installation** section.


## Local Installation

### Ubuntu 

1. Clone this github repo:

   ```sh
   cd ~
   git clone https://github.com/ankitvedak/Lidar_obstacle_detection_of_on_objects.git
   ```


2. Execute the following commands in a terminal

   ```shell
   sudo apt install libpcl-dev
   cd ~/Lidar_obstacle_detection_of_on_objects
   mkdir build && cd build
   cmake ..
   make
   ./environment
   ```

   This should install the latest version of PCL. You should be able to do all the classroom exercises and project with this setup.
   
