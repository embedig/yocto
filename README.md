# yocto

mkdir ebox-scada && cd ebox-scada
~/.bin/repo init -u https://github.com/embedig/yocto -m manifest-raspberrypi4-64.xml
~/.bin/repo sync
MACHINE=raspberrypi4-64 bitbake core-image-base
