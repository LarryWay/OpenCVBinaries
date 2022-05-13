# OpenCVBinaries

First things to do on a fresh flash
1. Update the OS
2. Enable legacy camera

Required Dependencies:
sudo apt install libtiff-dev zlib1g-dev
sudo apt install libjpeg-dev libpng-dev
sudo apt install libavcodec-dev libavformat-dev libswscale-dev libv4l-dev
sudo apt-get install libxvidcore-dev libx264-dev

Required Applications:
sudo apt install git
sudo apt install make

Clone repository
git clone https://github.com/LarryWay/OpenCVBinaries.git

Final Commands
sudo make install
sudo ldconfig
sudo apt-get update

