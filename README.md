#Setting up a minimal tree for building TWRP


###To initialize the main repository:

````
repo init -u https://github.com/goayandi/TWRP-manifest.git -b master
````
```````
repo sync 
```````
BUILDING IT FOR WIKO HIGHWAY SIGNS s4750 

$ cd [twrp source which synced from above]

$ source build/envsetup.sh 

$ lunch omni_s4750-userdebug 

$ make clean && make -j# recoveryimage  [# : no. of cpu cores ] 
