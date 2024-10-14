To initialize your local repository use
---------------------------------------

    git clone https://github.com/ObsidianMaximus/local_manifest.git -b crdroid-14 .repo/local_manifests
    

Then to sync up:
----------------

    repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all
