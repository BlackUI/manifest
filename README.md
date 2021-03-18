# BlackUI #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/BlackUI/manifest -b naish

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
