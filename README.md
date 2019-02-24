# DSO: Direct Sparse Odometry

For more information see
[https://vision.in.tum.de/dso](https://vision.in.tum.de/dso)

### Related Papers
* **Direct Sparse Odometry**, *J. Engel, V. Koltun, D. Cremers*, In arXiv:1607.02565, 2016
* **A Photometrically Calibrated Benchmark For Monocular Visual Odometry**, *J. Engel, V. Usenko, D. Cremers*, In arXiv:1607.02555, 2016

Get some datasets from [https://vision.in.tum.de/mono-dataset](https://vision.in.tum.de/mono-dataset) .

Additional dependecy: PCL

The usage is same as original [repo](https://github.com/JakobEngel/dso).
I've added save option to pangolin gui also a keyboard shortcut which "s".
I've tested with ROS2 and it works. I will put ROS2 version of dso\_ros
but it is not as polished as dso\_ros because I was testing ROS2 and tried to
make it work.

Note:
Arch Linux uses OpenCV 4.x and Ubuntu used OpenCV 3.x so I had to change
some of the variables in OpenCV libraries if it doesn't compile for you 
just change the OpenCV files with the original.

Example point cloud from pcl\_viewer
![Example](https://raw.githubusercontent.com/goktug97/dso/blob/master/example.png)



### License
DSO was developed at the Technical University of Munich and Intel.
The open-source version is licensed under the GNU General Public License
Version 3 (GPLv3).
For commercial purposes, we also offer a professional version, see
[http://vision.in.tum.de/dso](http://vision.in.tum.de/dso) for
details.
