## [Intel RealSense SDK 2.0](https://www.intelrealsense.com/sdk-2/)

Tools provided in the SDK are: viewer, depth quality tool and calibration.

### [Linux Distribution](https://github.com/IntelRealSense/librealsense/blob/master/doc/distribution_linux.md)
Follow the link provided to install it on linux.

- Intel RealSense Viewer

    Quickly access your Intel RealSense depth camera to view the depth stream, visualize point clouds, record and playback streams, configure your camera settings and more. Find the user's guide [here](https://www.intelrealsense.com/download/7144/).
After installation run it in the terminal:
```
realsense-viewer
```
    
After running it, you jave control over plenty of things. Use the guide and check the videos in the [Intel Realsense](https://www.youtube.com/c/IntelRealSense) YouTube channel.

### Recording with viewer

The Saved files will be in the `.bag` format. Bathymetric Attributed Grid (BAG) is a file format designed to store and exchange bathymetric data. It stores the msg file of the corresponding message data.  This format can be transformed into JPEG using [rosbag](http://wiki.ros.org/rosbag/Tutorials/Exporting%20image%20and%20video%20data).
