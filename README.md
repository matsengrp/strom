
## System prerequisites

    apt-get install libtool
    apt-get install libboost-all-dev
    apt-get install libeigen3-dev


## NCL

    git clone https://github.com/mtholder/ncl.git
    cd ncl
    sh bootstrap.sh
    ./configure
    make
    make check
    sudo make install


## Building C++ source

autoreconf -i

