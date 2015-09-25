CyanogenMod 10.1 for Ainol Novo 10 Hero II(v2,Samsung)
==================================================

Getting Started
---------------

To get started with Android/CyanogenMod, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

Then to sync and build:

    repo init -u git://github.com/iBullRay/manifest_mangov2.git -b cm-10.1
    repo sync -j*(where * - number of streams per cores,e.g quad core - -j5)
    sh vendor/cm/get-prebuilts
    source build/envsetup.sh
    lunch cm_mangov2-userdebug
    mka bacon