#Magdeoz TWRP-Multirom tree for Moto (2014)

##Building:
````
source build/envsetup.sh
lunch omni_condor-userdebug
make clean
make installclean
make -j10 recoveryimage
````
