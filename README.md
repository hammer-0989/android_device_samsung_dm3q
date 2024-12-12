# TWRP Device Tree for Samsung Galaxy S23 Ultra

[Userdata AIO Install Instructions](https://xdaforums.com/t/sm-s918b-0-one-ui-6-1-userdata_aio-odin-flashable-to-remove-encryption-make-rom-rw-install-twrp-root-use-on-stock-firmware-unlocked-bootloaders.4610061/)

# Special Thanks 
[jrkruse](https://xdaforums.com/m/jrkruse.1949695/) For userdata aio script.

# Kernel source 
[Here](https://github.com/samsung-sm8550/kernel_samsung_sm8550-commom.git)

## Clone repo
```bash 
git clone -b android-12.1 https://github.com/hammer-0989/twrp_device_samsung_dm3q device/samsung/dm3q
```

## To build 
```bash
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_dm3q-eng
mka recoveryimage
```
