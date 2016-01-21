#Magdeoz TWRP multirom tree for Moto E (2014)

##Building:
````
source build/envsetup.sh
lunch omni_otus-userdebug
make clean
make installclean
make -j10 recoveryimage
````
