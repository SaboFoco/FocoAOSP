# FocoAOSP-version of Lantern-aosp for our m8
Project for htc one m8 thanks to fabio-san from Lantern aosp
The Lantern Aosp Project Marshmallow 6.0

To initialize your local repository using the AOSP trees, use a command like this:

repo init -u https://github.com/L-Aosp/manifest.git -b M-6.0

Add Htc One M8 resources by typing this:
curl --create-dirs -L -o .repo/local_manifests/htc-msm8974.xml -O -L https://raw.githubusercontent.com/FocoAOSP/blob/SaboFoco-patch-1-6.0/htc-msm8974.xml

Then to sync up:

repo sync

Finally to build:

./build.sh device_m8

