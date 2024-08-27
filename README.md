To Initialize:
--------------

    git clone --depth=1 https://github.com/veux-frost-testzone/local_manifests.git -b voltage-14 .repo/local_manifests


To Sync:
--------

    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags

