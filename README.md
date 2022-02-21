# motion-planning-project
This repo contains our work on the course project for the RBE550 Motion Planning course at WPI 

### Set-up
[Dual-boot Ubuntu](https://www.tecmint.com/install-ubuntu-alongside-with-windows-dual-boot/)
(**Note**: The only thing you might want to do differently here is to make at least 120,000 MB of space at 
the start in step 3. 20,000 MB will be a little too low)

[Run CARLA on Google Cloud Platform](https://github.com/MichaelBosello/carla-colab/blob/master/carla-simulator.ipynb)

This was a good reference for setting up CARLA on GCP, although I had to make some modifications along the way:
- Install TurboVNC version-2.2.6 (Newer versions didn't work on Ubuntu 20.04)
- Install CARLA-0.9.8 (Newer versions have dropped support for OpenGL-3)

### Potentially useful tutorials:

##### ROS

- [ROS Tutorials](http://wiki.ros.org/ROS/Tutorials)
- [Connecting ROS & Gazebo](http://gazebosim.org/tutorials?cat=connect_ros)
- [Using ROSLaunch to spawn models](http://gazebosim.org/tutorials?tut=ros_roslaunch&cat=connect_ros)
- [ROS Motion Planning package](http://wiki.ros.org/navigation)

##### GAZEBO

- [Guided Tutorials](http://gazebosim.org/tutorials?cat=guided_b)
- [Programmatic World Control](http://gazebosim.org/tutorials?tut=plugins_world_properties&cat=write_plugin)
- [Writing a Plugin](http://gazebosim.org/tutorials?cat=write_plugin)
- [Control Plugin](http://gazebosim.org/tutorials?cat=guided_i&tut=guided_i5)
- [Car Models](https://github.com/ayushgaud/gazebo_cars)

### Contributors:
  - Alex Jensen
  - Radha Saraf
  - Amey Deshpande
