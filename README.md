Initialize after init repo roms

```
git clone https://github.com/Gartenn/manifest.git -b A16 .repo/local_manifests/
```

And sync repo
```
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```
