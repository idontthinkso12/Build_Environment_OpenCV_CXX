# Build_Environment_OpenCV_CXX
This repo provides tutorials on building environment of OpenCV (C++) on Windows and Mac (Both Intel and Apple silicon)

## on Windows
**Reference**

1. [【C/C++】VS Code配置Opencv用于机器视觉数字图像处理技术](https://blog.csdn.net/qq_37365857/article/details/103490774?utm_medium=distribute.pc_relevant.none-task-blog-2~default~baidujs_baidulandingword~default-4-103490774-blog-124402319.pc_relevant_3mothn_strategy_and_data_recovery&spm=1001.2101.3001.4242.3&utm_relevant_index=7)

2. [MinGW C++ Download and Installation](https://www.ics.uci.edu/~pattis/common/handouts/mingweclipse/mingw.html)

### **System Configurations**

**OS**: Windows11 22H2

**Text Editor**: Visual Studio Code 1.75.0

**Build Tool**: Cmake 3.26.0-rc 1

**Compiler**: gcc/g++ (8.1.0) by MinGW 

### **I. Preparation**
We need to make sure the following parts are installed: 1. Visual Studio Code (aka VS code) 2. MinGW 3. OpenCV 4. CMake

**I.1 Install VS code**

VS code is a handy and versitile text editor. It can be downloaded from the official website at [https://code.visualstudio.com/download](https://code.visualstudio.com/download)
Open VS code, go to "Extensions" and search "c/c++". Install the C/C++ extension provided by Microsoft. After the installation, researt VS code.

<p align="center">
  <img src="./screenshot/win/win_1.png">
</p>

**I.2 Install OpenCV**

OpenCV can be downloaded at [https://opencv.org/releases](https://opencv.org/releases/). Follow the onscreen instructions and finalizae the installation. **Make sure you note the installation path.** In my case, it is installed at `D:\opencv`. This location is denoted as `$CV$` in the rest of this tutorial for Windows.

<p align="center">
  <img src="./screenshot/win/win_2.png">
</p>

Then you want to create a new folder under `$CV$/build/x64` called `MinGW` (it is empty as of now).

<p align="center">
  <img src="./screenshot/win/win_3.png">
</p>

**I.3 Install CMake**
CMake can be downloaded at [https://cmake.org/download](https://cmake.org/download/). Follow the onscreen instructions and finalizae the installation.

<p align="center">
  <img src="./screenshot/win/win_4.png">
</p>


