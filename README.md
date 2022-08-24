# OrangeFox Recovery Project

### How to build ###

```bash
# Create dirs
$ mkdir ofox ; cd ofox

# Init repo
$ repo init --depth=1 -u https://gitlab.com/OrangeFox/Manifest.git -b fox_9.0

# Clone j7xelte repo
$ git clone https://gitlab.com/OrangeFox/device/j7xelte.git -b fox_9.0 device/samsung/j7xelte

# Sync
$ repo sync --no-repo-verify -c --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -j`nproc`

# Build
$ mv device/samsung/j7xelte/build_ofox.sh .
$ . build_ofox.sh j7xelte
```

## Credits
2019 @Astrako

## Contact
Telegram support group: [offline]
