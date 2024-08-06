# README

Build Instructions (RDK-B on Raspberry Pi)

mkdir <workspace dir>
cd <workspace dir>
repo init -u https://code.rdkcentral.com/r/manifests -m rdkb-raspberrypi.xml -b krogoth
repo sync -j4 --no-clone-bundle
source meta-cmf-raspberrypi/setup-environment (Select option raspberrypi-rdk-broadband.conf)
bitbake rdk-generic-broadband-image
