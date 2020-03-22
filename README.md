# Simple Qt App

## Install Qt
Is preinstalled on Raspian

But had to:
```shell
sudo apt-get install qt5-default
```

## Create project file
```shell
qmake -project
```

## Build
```shell
make
```

## Issues
Got the error message: `libEGL warning: GLX/DRI2 failed to authenticate`

Followed this guide: https://pi3d.github.io/html/FAQ.html#glx-dri2-not-supported-or-failed-to-authenticate

## Running program on the Pi
Cant start a program using GUI (the X Window server) from an ssh connection it seems. Need to run it on the actual pi.

## Refs
Ref doc: https://www.linux.org/threads/c-tutorial-create-qt-applications-without-qtcreator.18409/