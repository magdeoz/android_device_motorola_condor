#Magdeoz TWRP tree for Moto E (2014)

##Building:
````
source build/envsetup.sh
lunch omni_condor-userdebug
make clean
make installclean
make -j10 recoveryimage
````
