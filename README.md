## TWRP device tree for Samsung Galaxy Note 4 Duos (Snapdragon)
## trlteduosctc, trlteduoszc, trlteduoszh, trlteduoszn

Add to `.repo/local_manifests/trlteduos.xml`:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
  <project name="ripee/twrp_android_device_samsung_trlteduos" path="device/samsung/trlteduos" remote="github" revision="android-7.1" />
</manifest>
```

Then run `repo sync` to check it out.

To build:

```sh
. build/envsetup.sh
lunch omni_trlteduos-eng
mka recoveryimage
```

