To initialize your local repository use
---------------------------------------

    git clone https://github.com/ObsidianMaximus/local_manifest.git -b master .repo/local_manifests
    

Then to sync up:
----------------

    repo sync --force-sync -j12 --current-branch --no-tags --no-clone-bundle --optimized-fetch --force-broken
