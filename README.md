# OpenCVBinaries

Raspberry pi flash
Version: Raspberry Pi OS Lite (64 bit)


First things to do on a fresh flash
1. Update the OS
2. Enable legacy camera

Required Dependencies:
- sudo apt install libtiff-dev zlib1g-dev
- sudo apt install libjpeg-dev libpng-dev
- sudo apt install libavcodec-dev libavformat-dev libswscale-dev libv4l-dev
- sudo apt-get install libxvidcore-dev libx264-dev

Required Applications:
- sudo apt install git
- sudo apt install make

Clone / get repositories
- git clone https://github.com/LarryWay/OpenCVBinaries.git
- wget https://github.com/opencv/opencv/archive/4.x.zip
- unzip 4.x.zip
- rm -rf 4.x.zip
- 

Final Commands:
- sudo make install
- sudo ldconfig
- sudo apt-get update

