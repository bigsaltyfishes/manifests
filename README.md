## Yuyuko's AOSP Mod

### Getting Started

To get started with the AOSP Mod sources, you'll need to get familiar with [Git and Repo, and AOSP building](https://source.android.com/setup/build/downloading).

#### 1. Initialize your local repository

```
repo init -u https://github.com/YuyukoAOSPMod/manifests -b 13
```

### 2. Sync the code

```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### 3. When finished, clone your device sources repositories

### 4. Initialize build environment using envsetup.sh

```
. build/envsetup.sh
```

### 5. Lunch device

```
lunch aosp_<$device_name>-<$buildtype>
```

### 6. Grab some cookies and coffee and wait until build complete :D

```
mka bacon 
```

---

## Credits

- [Android Open Source Project](https://android.googlesource.com/)
- [ArrowOS](https://github.com/ArrowOS)

- [LineageOS](https://github.com/LineageOS)

- [PixelExperience](https://github.com/PixelExperience)
- [Project-Kaleidoscope](https://github.com/Project-Kaleidoscope)
- [ProtonAOSP](https://github.com/ProtonAOSP)
- [Acme UI](https://github.com/AcmeUI/)


