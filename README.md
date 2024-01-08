Init project:
repo init -u https://github.com/ipz-automotive/ipz-manifest -b main -m default.xml

Sync project:
repo sync -j8

Manifests:
    googlesource/ - AOSP branch android-14.0.0_r20
    raspberry-vanilla/ - AOSP for RPI4 branch android-14.0
    ipz-automotive/ - project repos

RPI4 sources:
https://github.com/raspberry-vanilla/android_local_manifest