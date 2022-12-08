FROM osrf/ros:galactic-desktop

RUN apt-get update && apt-get -y upgrade &&\
    apt-get install -y linux-tools-5.4.0-77-generic hwdata

RUN update-alternatives --install /usr/local/bin/usbip usbip /usr/lib/linux-tools/5.4.0-77-generic/usbip 20

RUN apt-get update && apt-get install -y usbutils && lsusb &&\
    apt-get install -y udev &&\
    apt-get install -y screen


