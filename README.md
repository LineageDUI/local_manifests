# DUI Local Manifest

Simply place **dui.xml** into the **.repo/local_manifests** directory of your LineageOS
ROM directory. This will bring in the DUI-specific files from LineageDUI and build them along
with your ROM.

Note that you will still have to cherry-pick the appropriate commits to the projects of your
LineageOS ROM (such as **android_frameworks_base** and **android_packages_apps_Settings**).