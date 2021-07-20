# Daemon-OS  

## Getting source code

First, make sure you have an [Android build environment](https://source.android.com/setup/build/initializing) and the [repo tool](https://source.android.com/setup/build/downloading) set up. After that, run the following commands:

```
repo init -u ssh://git@github.com/Daemon-OS/platform_manifest.git -b reactor
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
### SSH ONLY  kthnxBye