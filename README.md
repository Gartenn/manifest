Initialize after init repo roms

git clone https://github.com/PeridotSupremacy/manifest.git -b lineage-23.0 .repo/local_manifests/
And sync repo

repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
