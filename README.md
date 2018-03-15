## TWRP device tree for Samsung Galaxy S9 (starlte)

```
repo init -u https://github.com/omnirom/android.git -b android-8.1
```

Then run `repo sync` to check it out.

To build:

```sh
. build/envsetup.sh
lunch omni_starlte-eng && mka recoveryimage
```
