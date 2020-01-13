# Opencv-ffmpeg-and-Cuda-installation-
--------------------
Useful webpages
--------------------

https://developer.nvidia.com/ffmpeg

https://trac.ffmpeg.org/wiki/CompilationGuide/Ubuntu#FFmpeg

https://askubuntu.com/questions/61396/how-do-i-install-the-nvidia-drivers

https://www.cerebrumedge.com/single-post/2017/12/26/Compiling-OpenCV-with-CUDA-and-FFMpeg-on-Ubuntu-1604

--------------------
Check NVIDIA graphics card
--------------------
lspci | grep VGA

Then refer to https://en.wikipedia.org/wiki/CUDA#GPUs_supported
for micro-architecture name, e.g., Kepler, Maxwell, Pascal, etc.

--------------------
Dependency Installations

DO NOT FORGET TO RESTART YOUR PC EVERY SO OFTEN DURING - VERY USEFUL!

sudo apt-get update 

sudo shutdown -r now
--------------------

sudo apt-get update 

sudo apt-get install git

sudo apt-get install libx264-dev 

sudo apt-get install libx265-dev

sudo apt-get install libvpx-dev 

sudo apt-get install autoconf

sudo apt-get install build-essential cmake libass-dev pkg-config 

sudo apt-get install libsdl2-dev libtool libva-dev libvdpau-dev libvorbis-dev

sudo apt-get install libsdl2-dev libtool

sudo apt-get install libsdl2-dev libtool libva-dev libvdpau-dev libvorbis-dev 

sudo apt-get install libxcb1-dev libxcb-shm0-dev libxcb-xfixes0-dev texinfo wget zlib1g-dev 

sudo apt-get install yasm

sudo apt-get install libgstreamer1.0-dev libgstreamer-plugins-base1.0-dev 

sudo apt-get install libeigen3-dev 

sudo apt-get install freeglut3 freeglut3-dev 

sudo apt-get install libglu1-mesa-dev 

sudo apt-get install libglu1-mesa

sudo apt-get install libglew1.13 

sudo apt-get install libgl1-mesa-dev

sudo apt-get install libxcb1-dev libxcb-shm0-dev libxcb-xfixes0-dev texinfo wget zlib1g-dev

sudo apt-get install libjpeg8-dPascalev libtiff5-dev libjasper-dev libpng12-dev 

sudo apt-get install libavcodec-dev 

sudo apt-get install libavformat-dev 

sudo apt-get install libswscale-dev libv4l-dev 

sudo apt-get install libxvidcore-dev 

sudo apt-get install libgtk-3-dev 

sudo apt-get install libatlas-base-dev gfortran

sudo apt-get install libgtkglext1

sudo apt-get install libgtkglext1-dev 

sudo apt-get install libgl1-mesa-dev

sudo apt-get install libglu1-mesa-dev

sudo apt-get install libqtcore4 libqtgui4

sudo apt-get install libpython3.5

sudo apt-get install libpython3.5-dev

sudo apt-get install python3-numpy

sudo apt-get install python3.5-numpy

sudo apt-get install python3-scipy

sudo apt-get install qt5-default 

sudo apt-get install libavresample-dev 

sudo apt-get install libpython2.7-dev 

sudo apt-get install python-numpy

sudo apt-get install python-scipy

sudo apt-get install libyaml-cpp-dev

sudo apt-get install ros-kinetic-image-transport

sudo apt-get install comerr-dev hdf5-helpers javascript-common krb5-multidev libaec-dev libaec0 libarmadillo6 libarpack2 libcurl4-gnutls-dev libdap-dev libdap17v5 libdapclient6v5 libdapserver7v5 libepsilon1 libfreexl1 libgdal-dev libgdal1i libgeos-3.5.0 libgeos-c1v5 libgeos-dev libgif-dev libgl2ps-dev libgl2ps0 libgssrpc4

sudo apt-get install libhdf4-0-alt libhdf4-alt-dev libhdf5-10 libhdf5-cpp-11 libhdf5-dev libhdf5-mpi-dev libhdf5-openmpi-10 libhdf5-openmpi-dev libjs-jquery libjs-sphinxdoc libjs-underscore libjsoncpp-dev libkadm5clnt-mit9 libkadm5srv-mit9 libkdb5-8 libkmlbase1 libkmldom1 libkmlengine1 libminizip1 libmysqlclient-dev

sudo apt-get install libnetcdf-c++4 libnetcdf-cxx-legacy-dev libnetcdf-dev libnetcdf11 libogdi3.2 libopenjp2-7 libpq-dev libpq5 libproj9 libqt5clucene5 libqt5designer5 libqt5designercomponents5 libqt5help5 libqt5quickparticles5 libqt5quickwidgets5 libqt5webkit5-dev libspatialite-dev libspatialite7 libsqlite3-dev libssl-dev

sudo apt-get install libssl-doc libsuperlu4 libsz2 libtheora-dev liburiparser1 libvtk6-dev libvtk6-java libvtk6-qt-dev libvtk6.2 libvtk6.2-qt

sudo apt-get install libwebp-dev libxerces-c-dev libxerces-c3.1 odbcinst odbcinst1debian2 proj-bin proj-data

sudo apt-get install python-attr python-autobahn python-cffi-backend python-concurrent.futures python-cryptography python-enum34 python-idna python-ipaddress python-lz4 python-mpi4py python-msgpack python-openssl python-pam python-pyasn1 python-pyasn1-modules python-serial python-service-identity python-snappy python-trollius python-twisted python-twisted-bin python-twisted-core python-txaio python-vtk6 python-zope.interface

sudo apt-get install qtdeclarative5-dev qttools5-dev qttools5-private-dev

sudo apt-get install tcl-dev tcl-vtk6 tcl8.6-dev tk-dev tk8.6-dev unixodbc unixodbc-dev vtk6

sudo apt-get install python-vtk

sudo apt-get install libgphoto2-dev

sudo apt-get install libprotobuf-dev

sudo apt-get install vtk6

sudo apt-get install libvtk6-dev 

sudo apt-get install python-vtk

sudo apt-get install libvtk6-dev python-vtk6 

sudo apt-get install libvtk6.2

sudo apt-get install libsdl-image1.2-dev libsdl-dev

sudo apt-get install libusb-1.0-0

sudo apt-get install libusb-1.0-0-dev 

sudo apt-get install libusb-dev

sudo apt-get install libccd-dev libccd2 libfcl-0.5-dev libfcl0.5 libflann-dev libflann1.8 libglew-dev libqhull-dev libqhull7

sudo apt-get install libcurl3

sudo apt-get install curl 

sudo apt-get install libtinyxml-dev 


--------------------
Install correct NVIDIA Graphics Driver
--------------------

sudo add-apt-repository ppa:graphics-drivers/ppa

sudo apt-get update 

sudo apt-get upgrade

---------------
Check recommended driver
---------------

ubuntu-drivers devices | grep recommended

should give an output like: 
"driver   : nvidia-3xx - third-party non-free recommended"
where, xx is a two-digit number!

sudo apt-get install nvidia-3xx

sudo shutdown -r now

--------------------
Install CUDA
--------------------
Go to: https://developer.nvidia.com/cuda-toolkit
Click on "Download Now"
Then follow button clicks as per the PC and OS, e.g.,  Download Now --> Linux --> x86_64 --> Ubuntu --> 16.04 --> deb (local)
Then, download the Base Installer and the patch (if there is one), e.g., click on Download (1.2 GB) as well as Download (96.3 MB)
Then, follow the below commands: 
(Note: these commands are for Ubuntu 16.04, 64-bit. The packages may be different for different OS's)

cd Downloads/

sudo dpkg -i cuda-repo-ubuntu1604-9-2-local_9.2.88-1_amd64.deb 

sudo apt-key add /var/cuda-repo-9-2-local/7fa2af80.pub

sudo apt-get update

sudo apt-get install cuda

sudo dpkg -i cuda-repo-ubuntu1604-9-2-local-cublas-update-1_1.0-1_amd64.deb 

sudo apt-get update

sudo apt-get upgrade cuda

sudo apt-get install cuda

sudo apt-get upgrade cuda

Copy the following three paths at the end of ~/.bashrc file 

export LD_LIBRARY_PATH="/usr/lib:/usr/local:/usr/local/lib:$LD_LIBRARY_PATH"

export LD_LIBRARY_PATH="/usr/local/cuda-9.2/lib64:$LD_LIBRARY_PATH"

export PATH="/usr/bin:/usr/local/cuda-9.2/bin:$PATH"

Pascal
Check CUDA installation with

nvcc --version

--------------------
Install NVIDIA SDK
--------------------
Method 1: 
---------
Download SDK from NVIDIA NVENC developer site: 
https://developer.nvidia.com/nvidia-video-codec-sdk

Version 8.2.15 of SDK is included with these instructions
The ReadMe.txt file in the folder has instructions for linux. 

- Make sure to copy the "nvEncodeAPI.h", "cuviddec.h", and "nvcuvid.h" to a standard system include folder (e.g. /usr/local/include)
- Also, as given in ReadMe.txt  
    * Add the directory (/usr/local/lib/pkgconfig by default) to the PKG_CONFIG_PATH environment variable. This is required by the Makefile to determine the include paths for the FFmpeg headers.
    * Add the directory where the FFmpeg libraries are installed, to the LD_LIBRARY_PATH environment variable. This is required for resolving runtime dependencies on FFmpeg libraries.
---------
Method 2: 
---------
The SDK is also maintained on git!

cd Downloads/

git clone https://git.videolan.org/git/ffmpeg/nv-codec-headers.git

cd nv-codec-headers/

make

sudo make install

The git version will only install the headers, not the libraries, inside /usr/local/include/ffnvcodec.
 
Maybe a good idea to replace, "nvEncodeAPI.h", "dynlink_cuviddec.h", "dynlink_nvcuvid.h", with those from the downloaded NVIDIA SDK folder

--------------------
Install FFMPEG
--------------------

cd Downloads/

git clone https://git.ffmpeg.org/ffmpeg.git

cd ffmpeg/

git checkout release/4.0

PKG_CONFIG_PATH="/usr/local/lib/pkgconfig" ./configure --bindir="/usr/bin" --enable-cuda --enable-cuvid --enable-nvenc --enable-nonfree --enable-libnpp --extra-cflags=-I/usr/local/include --extra-ldflags=-L/usr/local/lib --extra-libs="-lpthread -lm" --enable-gpl --enable-shared --enable-libass --enable-libx264 --enable-libvorbis --enable-libvpx --enable-libx265

-------------------The above configuration is changed by the lower

PKG_CONFIG_PATH="/usr/local/lib/pkgconfig" ./configure --bindir="/usr/bin" --enable-cuda --enable-cuvid --enable-nvenc --enable-nonfree --enable-libnpp --extra-cflags=-I/usr/local/cuda-9.2/include --extra-cflags=-I/usr/local/include --extra-ldflags=-L/usr/local/cuda-9.2/lib64 --extra-libs="-lpthread -lm" --enable-gpl --enable-shared --enable-libass --enable-libx264 --enable-libvorbis --enable-libvpx --enable-libx265 --enable-libkvazaar

--------------------
If there is an error

ERROR: kvazaar >= 0.8.1 not found using pkg-config

-------------------
cd Downloads/

git clone https://github.com/ultravideo/kvazaar.git

cd kvazaar/

./autogen.sh

./configure

make

sudo make install

cd Downloads/ffmpeg

PKG_CONFIG_PATH="/usr/local/lib/pkgconfig" ./configure --bindir="/usr/bin" --enable-cuda --enable-cuvid --enable-nvenc --enable-nonfree --enable-libnpp --extra-cflags=-I/usr/local/cuda/include --extra-cflags=-I/usr/local/include --extra-ldflags=-L/usr/local/cuda/lib64 --extra-libs="-lpthread -lm" --enable-gpl --enable-shared --enable-libass --enable-libx264 --enable-libvorbis --enable-libvpx --enable-libx265 --enable-libkvazaar

make 

sudo make install

--------------------
Install OPENCV w/ FFMPEG and CUDA enabled
--------------------

Add the following dynamic links to the nvcuvid libraries.
---------

`sudo ln -s /usr/lib/nvidia-410/libnvcuvid.so /usr/lib/libnvcuvid.so`

`sudo ln -s /usr/lib/nvidia-410/libnvcuvid.so.1 /usr/lib/libnvcuvid.so.1`

Replace nvidia-xxx with the latest nvidia driver you installed above, i.e., nvidia-390, nvidia-396, etc.

---------

`cd Downloads/`

`git clone https://github.com/opencv/opencv.git`

`cd opencv/`

`git checkout 3.3.1`

`cd ../`

`git clone https://github.com/opencv/opencv_contrib.git`

`cd opencv_contrib/`

`git checkout 3.3.1`

`cd ~/Downloads/opencv/`

`mkdir build`

`cd build`

`cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local -D INSTALL_C_EXAMPLES=ON -D INSTALL_PYTHON_EXAMPLES=OFF -D OPENCV_EXTRA_MODULES_PATH=~/Downloads/opencv_contrib/modules -D BUILD_EXAMPLES=ON -D BUILD_opencv_python2=ON -D BUILD_opencv_python3=ON -D FORCE_VTK=ON -D WITH_FFMPEG=ON -D WITH_GSTREAMER=ON -D WITH_CUDA=ON -D CUDA_GENERATION=Pascal -D WITH_OPENGL=ON -D WITH_QT=ON -D WITH_EIGEN=ON -D WITH_NVCUVID=ON -D ENABLE_FAST_MATH=1 -D CUDA_FAST_MATH=1 -D WITH_CUBLAS=1 -D WITH_LAPACK=ON -D PYTHON_DEFAULT_EXECUTABLE=/usr/bin/python -D PYTHON_INCLUDE_DIR=/usr/include/python2.7 -D PYTHON3_INCLUDE_DIR=/usr/include/python3.5m -D PYTHON_LIBRARY=/usr/lib/x86_64-linux-gnu/libpython2.7.so.1 -D PYTHON3_LIBRARY=/usr/lib/x86_64-linux-gnu/libpython3.5m.so -D PYTHON_PACKAGES_PATH=/usr/lib/python2.7 -D PYTHON3_PACKAGES_PATH=/usr/lib/python3.5 -D PYTHON_NUMPY_INCLUDE_DIRS=/usr/lib/python2.7/dist-packages/numpy/core/include -D PYTHON3_NUMPY_INCLUDE_DIRS=/usr/lib/python3/dist-packages/numpy/core/include ..`

make -j8

------------If there is an error regarding (error: ‘CODEC_FLAG_GLOBAL_HEADER’ and error: ‘AVFMT_RAWPICTURE’)---

Copy and paste this code

--------------------------------
`
#define AV_CODEC_FLAG_GLOBAL_HEADER (1 << 22)

#define CODEC_FLAG_GLOBAL_HEADER AV_CODEC_FLAG_GLOBAL_HEADER

#define AVFMT_RAWPICTURE 0x0020
`
---------------------------------

To the top of: opencv/modules/videoio/src/cap_ffmpeg_impl.hpp

`sudo make install`

--------------------
Install OPENCV3.1.0 w/ FFMPEG and CUDA enabled
--------------------

Add the following dynamic links to the nvcuvid libraries.(This will depend on the type of nvidia driver installed)
---------

`sudo ln -s /usr/lib/nvidia-410/libnvcuvid.so /usr/lib/libnvcuvid.so`

`sudo ln -s /usr/lib/nvidia-410/libnvcuvid.so.1 /usr/lib/libnvcuvid.so.1`


Replace nvidia-xxx with the latest nvidia driver you installed above, i.e., nvidia-390, nvidia-396, etc.

---------

`cd Downloads/`

`git clone https://github.com/opencv/opencv.git`

`cd opencv/`

`git checkout 3.1.0`

`cd ../`

`git clone https://github.com/opencv/opencv_contrib.git`

`cd opencv_contrib/`

`git checkout 3.1.0`

`cd ~/Downloads/opencv/`

`mkdir build`

`cd build`

`cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local -D INSTALL_C_EXAMPLES=ON -D INSTALL_PYTHON_EXAMPLES=OFF -D OPENCV_EXTRA_MODULES_PATH=~/Downloads/opencv_contrib/modules -D BUILD_EXAMPLES=ON -D BUILD_opencv_python2=ON -D BUILD_opencv_python3=ON -D FORCE_VTK=ON -D WITH_FFMPEG=ON -D WITH_GSTREAMER=ON -D WITH_CUDA=ON  -D ENABLE_CXX11=ON -D CUDA_GENERATION=Pascal -D WITH_OPENGL=ON -D WITH_QT=ON -D WITH_EIGEN=ON -D WITH_NVCUVID=ON -D ENABLE_FAST_MATH=1 -D CUDA_FAST_MATH=1 -D WITH_CUBLAS=1 -D WITH_LAPACK=ON -D PYTHON_DEFAULT_EXECUTABLE=/usr/bin/python -D PYTHON_INCLUDE_DIR=/usr/include/python2.7 -D PYTHON3_INCLUDE_DIR=/usr/include/python3.5m -D PYTHON_LIBRARY=/usr/lib/x86_64-linux-gnu/libpython2.7.so.1 -D PYTHON3_LIBRARY=/usr/lib/x86_64-linux-gnu/libpython3.5m.so -D PYTHON_PACKAGES_PATH=/usr/lib/python2.7 -D PYTHON3_PACKAGES_PATH=/usr/lib/python3.5 -D PYTHON_NUMPY_INCLUDE_DIRS=/usr/lib/python2.7/dist-packages/numpy/core/include -D PYTHON3_NUMPY_INCLUDE_DIRS=/usr/lib/python3/dist-packages/numpy/core/include ..
`
-----------------------------------------------------------------------------------------------
		IF errors regarding C++11 support use this
		
`cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local -D INSTALL_C_EXAMPLES=ON -D INSTALL_PYTHON_EXAMPLES=OFF -D OPENCV_EXTRA_MODULES_PATH=/home/yonas/Downloads/opencv_contrib/modules -D BUILD_EXAMPLES=ON -D BUILD_opencv_python2=ON -D BUILD_opencv_python3=ON -D FORCE_VTK=ON -D WITH_FFMPEG=ON -D WITH_GSTREAMER=ON -D WITH_CUDA=ON  -D ENABLE_CXX11=ON -D CUDA_GENERATION=Kepler -D WITH_OPENGL=ON -D WITH_QT=ON -D WITH_EIGEN=ON -D WITH_NVCUVID=ON -D ENABLE_FAST_MATH=1 -D CUDA_FAST_MATH=1 -D WITH_CUBLAS=1 -D WITH_LAPACK=ON -D PYTHON_DEFAULT_EXECUTABLE=/usr/bin/python -D PYTHON_INCLUDE_DIR=/usr/include/python2.7 -D PYTHON3_INCLUDE_DIR=/usr/include/python3.5m -D PYTHON_LIBRARY=/usr/lib/x86_64-linux-gnu/libpython2.7.so.1 -D PYTHON3_LIBRARY=/usr/lib/x86_64-linux-gnu/libpython3.5m.so -D PYTHON_PACKAGES_PATH=/usr/lib/python2.7 -D PYTHON3_PACKAGES_PATH=/usr/lib/python3.5 -D PYTHON_NUMPY_INCLUDE_DIRS=/usr/lib/python2.7/dist-packages/numpy/core/include -DBUILD_LIBPROTOBUF_FROM_SOURCES=ON -D PYTHON3_NUMPY_INCLUDE_DIRS=/usr/lib/python3/dist-packages/numpy/core/include ..

-----------IF CMake Error: The following variables are used in this project, but they are set to NOTFOUND.
	   Please set them or make sure they are set and tested correctly in the CMake files:
	   CUDA_nppi_LIBRARY (ADVANCED)
     `
take a look at this link ==> https://stackoverflow.com/questions/46584000/cmake-error-variables-are-set-to-notfound

`make -j8`

------------If there is an error regarding (error: ‘CODEC_FLAG_GLOBAL_HEADER’ and error: ‘AVFMT_RAWPICTURE’)---

Copy and paste this code
--------------------------------
`
#define AV_CODEC_FLAG_GLOBAL_HEADER (1 << 22)
#define CODEC_FLAG_GLOBAL_HEADER AV_CODEC_FLAG_GLOBAL_HEADER
#define AVFMT_RAWPICTURE 0x0020`

---------------------------------
To the top of: opencv/modules/videoio/src/cap_ffmpeg_impl.hpp
--------------------
Install OPENCV4.2.0 In anaconda virtual enviroment
--------------------
`cd Downloads/`

`git clone https://github.com/opencv/opencv.git`

`cd opencv/`

`git checkout 4.2.0`

`cd ../`

`git clone https://github.com/opencv/opencv_contrib.git`

`cd opencv_contrib/`

`git checkout 4.2.0`

`cd ~/Downloads/opencv/`

`mkdir build`

`cd build`

`
cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local -D INSTALL_C_EXAMPLES=ON -D INSTALL_PYTHON_EXAMPLES=OFF -D OPENCV_EXTRA_MODULES_PATH=/media/user/Data/programs/opencv_contrib/modules -D BUILD_EXAMPLES=ON -D BUILD_opencv_python2=ON -D BUILD_opencv_python3=ON -D FORCE_VTK=ON -D WITH_FFMPEG=ON -D WITH_GSTREAMER=ON -D WITH_CUDA=ON -D ENABLE_CXX11=ON -D CUDA_GENERATION=Pascal -D WITH_OPENGL=ON -D WITH_QT=ON -D WITH_EIGEN=ON -D WITH_NVCUVID=ON -D ENABLE_FAST_MATH=1 -D CUDA_FAST_MATH=1 -D WITH_CUBLAS=1 -D WITH_LAPACK=ON -D PYTHON_DEFAULT_EXECUTABLE=/home/user/anaconda3/envs/my_env/bin/python -D PYTHON_INCLUDE_DIR=/home/user/anaconda3/envs/my_env/include -D PYTHON3_INCLUDE_DIR=/home/user/anaconda3/include/python3.7m -D PYTHON3_LIBRARY=/home/user/anaconda3/envs/my_env/lib/libpython3.7m.so .. `


`sudo make install`
