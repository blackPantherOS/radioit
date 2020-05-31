Compile on Linux.
-----------------------------------
blackPanther OS:

    intalling gcc-c++ gcc qtcore5-devel cmake taglib-devel boost-devel gettext \
    lastfm-devel gstreamer-devel gstreamer-plugins-base-devel \
    glew-devel qjson-devel gpod-devel \
    plist-devel mtp-devel usbmuxd-devel qttools5 cdio-devel \
    fftw3-devel sqlite3-devel"

Ubuntu:

    sudo apt-get install liblastfm-dev libtag1-dev gettext libboost-dev \
    libboost-serialization-dev libqt5-dev qt5-dev-tools libqt5-opengl-dev \
    cmake libgstreamer0.10-dev libgstreamer-plugins-base0.10-dev \
    libglew1.5-dev libqjson-dev libgpod-dev libplist-dev \
    libusbmuxd-dev libmtp-dev libcdio-dev \
    protobuf-compiler libprotobuf-dev libqca2-dev libqca2-plugin-ossl \
    libfftw3-dev libsparsehash-dev libsqlite3-dev
    
    
Fedora:

    su -c "yum install gcc-c++ liblastfm-devel taglib-devel gettext boost-devel \
    qt-devel cmake gstreamer-devel gstreamer-plugins-base-devel glew-devel \
    libgpod-devel qjson-devel libplist-devel \
    usbmuxd-devel libmtp-devel protobuf-devel protobuf-compiler qca2-devel \
    llibcdio-devel qca-ossl fftw-devel sparsehash-devel sqlite-devel"
    
    
openSUSE:

    sudo zypper install cmake libqt5-devel gcc gcc-c++ boost-devel liblastfm-devel \
    gettext-tools glew-devel taglib-devel gstreamer-0_10-devel \
    gstreamer-0_10-plugins-base-devel libmtp-devel ligpod-devel \
    libqjson-devel libplist-devel \
    libusbmuxd-devel libcdio-devel fftw3-devel protobuf-devel \
    libprotobuf-lite6 sqlite-devel
    
    
OpenMandriva/Mageia/Rosa/:

    su -c "urpmi gcc-c++ gcc libqt5-devel cmake libtaglib-devel boost-devel gettext \
    liblastfm-devel libgstreamer-devel libgstreamer-plugins-base-devel \
    libglew-devel libqjson-devel libgpod-devel \
    libplist-devel libmtp-devel libusbmuxd-devel qt5-linguist libcdio-devel \
    fftw3-devel sqlite-devel"
    
    
Pardus:

    sudo pisi it boost-devel gettext-devel gstreamer-devel liblastfm-devel \
    taglib-devel qt-devel cmake gst-plugins-base-devel glew-devel \
    libqjson-devel libgpod-devel libplist-devel \
    usbmuxd-devel libmtp-devel glibc-devel pkgconfig \
    libxml2-devel libusb-devel glib2-devel sqlite-devel \
    libcdio-devel libX11-devel kernel-headers zlib-devel fftw3-devel
    
    cd src
    qmake/qmake-qt5
    make -j


### Compilación de radit.

Ubuntu:

    sudo apt-get install build-essential
    sudo apt-get install libqt5-dev 
    sudo apt-get install libtag1-dev 
    sudo apt-get install qt5-dev-tools 

openSUSE:

    sudo zypper install cmake libqt5-devel gcc gcc-c++ taglib-devel 

Fedora:

    su -c "yum install gcc-c++  taglib-devel qt-devel"
    
### Salida de compilación.

    OBJECTS_DIR =../out
    MOC_DIR = ../out
    UI_DIR = ../out
    DESTDIR = ../out


### aacplus en linux.

There are Ubuntu packages for all the above tools, you just have to use this repository by
either editing /etc/apt/sources.list by hand or adding it to Synaptic or Adept

    apat-

and then run:

Hay que instalar gnome-mplayer antes de

    apt-get install mp4tools
    apt-get install mplayer
    p4tools: Depends: mplayer but it is not installable
             Depends: mencoder but it is not installable
             Depends: faac but it is not installable


Compile on Windows:
---------------------

    radioit.pro
    CONFIG += release


### Build.

    OBJECTS_DIR =..\out
    MOC_DIR = ..\out
    #UI_DIR = ..\out  ->compilation error may need to be comment/uncomment
    DESTDIR = ..\out

Enter command line using
    QT 5.x.x command prompt
    mingw32-make
or
    mingw64-make


