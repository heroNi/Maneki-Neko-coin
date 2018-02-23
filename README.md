manekinekocoin
ubuntu 16.04 build

Dependency List
sudo apt install build-essential libqt4-dev qt5-qmake cmake qttools5-dev libqt5webkit5-dev qttools5-dev-tools qt5-default python-sphinx texlive-latex-base inotify-tools openssl libssl-dev libdb++-dev libminiupnpc-dev git sqlite3 libsqlite3-dev g++ libpng-dev gedit python gcc make libbz2-dev libdb-dev libssl-dev libreadline-dev autoconf libtool libleveldb-dev libblkid-dev e2fslibs-dev libboost-all-dev libaudit-dev nano qtbase5-dev qt4-dev-tools libqtcore4 libqtgui4 automake -y﻿

#After install verify GCC and G++

gcc --version g++ --version

#readout should say version installed

#If system states none installed manually install

sudo apt install gcc

#or

sudo apt install g++

#Create a Sub Directory where you will store your CRYPTcoin

sudo mkdir CRYPTcoin

cd CRYPTcoin

#Once inside pull your git repo into the directory
