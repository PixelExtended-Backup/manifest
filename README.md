# Pixel Extended #
<img src="https://imgur.com/likQDEZ.png">

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/PixelExtended/manifest -b r

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
```
### Maintainership ###

If You wish to maintain PixelExtended For your device Officially , Contact @heisinbug on telegram with your trees and device name .

Some Things to Consider before applying :- 

1. Tree Should be maintained properly with authorship .
2. You should be able to fix your device specific issue on your own , saying "me nuub" isn't fun anymore.

That's it , Happy Cooking .
