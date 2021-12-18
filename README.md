# HeavensExperience

Project Heaven is another aftermarket AOSP ROM which basically offers minimal UI enhancement & close to Stock Android ROM with great performance, security and stability. Most of the OEMs' these days will provide slow and untimely updates, but we don't do that here. Project Heavens is an attempt to make the Android experience much better and different from the regular AOSP standard. We are very thankful to everyone else who helped Heavens. This a new User Experience and we hope you enjoy using Project Heavens!

To get started, you'll need to get
familiar with [Repo](https://source.android.com/source/using-repo.html) and [Version Control with Git](https://source.android.com/source/version-control.html).

---------------------------------------------------------------------------------------
 
# Setting up HeavensExperience source

To begin with you first have to initialize the repo:
 
```bash
repo init -u https://github.com/HeavensExperience/manifest.git -b 12.0
```

Then sync it up:

```bash
repo sync --force-sync --no-tags --no-clone-bundle -j$(nproc --all)
```

<b>Note: 
- You must have at least 120-150GB free space on your disk 
- Basic git knowledge</b>

Building HeavensExperience
==================

```bash
. build/envsetup.sh
lunch heavens_device-userdebug
mka heavens
```

Thank you for your contribution to HeavensExperience
---------------------------------------------------------------------------------------
 
 Team Project HeavensExperience
 ===============

 * [**Nadins**](https://t.me/NadinAlissa) - Core Developer
 * [**ToxicLord**](https://t.me/ToxicLord) - Core Developer

---------------------------------------------------------------------------------------
 Credits:
 =======
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**ProtonAOSP**](https://github.com/ProtonAOSP)
 * [**ArrowOS**](https://github.com/ArrowOS)
 
# Happy Building :)
---------------------------------------------------------------------------------------

