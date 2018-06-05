# opencv-3.4.1 winx64 build + open cv contrib

Right now, the binaries are available to download from https://1drv.ms/u/s!AkSFtNKJBDmNholSOzYFVvIW2aLhVA

After investing several hours learning how to build opencv + opencv contrib, here is the result. Hope you find it usefull!

To start developing just download opencv 3.4.1 source code from https://github.com/opencv/opencv/releases/tag/3.4.1-cvsdk and opencv contrib 3.4.1 from https://github.com/opencv/opencv_contrib/releases/tag/3.4.1.

Unzip both of them to a local directory eg: C:\OpenCV

Includes directory
C:\OpenCV\opencv-3.4.1\include

Others:

C:\OpenCV\opencv-3.4.1\modules\calib3d\include
C:\OpenCV\opencv_contrib-3.4.1\modules\aruco\include

For opencv_modules.hpp, include path to this directory (opencv-3.4.1.build): eg: C:\OpenCV\opencv-3.4.1.build

Add this directory to your system path: C:\OpenCV\opencv-3.4.1.build\bin\Debug

This is where to get .lib files
C:\OpenCV\opencv-3.4.1.build\lib\Debug

How to build applications with OpenCV inside the "Microsoft Visual Studio"
https://docs.opencv.org/3.4.1/dd/d6e/tutorial_windows_visual_studio_opencv.html
