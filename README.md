Nitrogen OS Maintenance Release 2 Manifest

To initialize your local repository use
---------------------------------------

    repo init -u https://github.com/tathanhlam66/android_manifest.git -b o2
    

Then to sync up:
----------------

    repo sync -j 16

Build command is
----------------
    export JACK_SERVER_VM_ARGUMENTS="-Dfile.encoding=UTF-8 -XX:+TieredCompilation -Xmx4000m"
    . build/envsetup.sh
    make -j 7 otapackage
-----------------
