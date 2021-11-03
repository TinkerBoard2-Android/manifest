# manifest

This repo is used to download manifests for Tinker Board 2/2S Android releases.

Please refer to the following URL to install Docker Engine on Ubuntu.

    https://docs.docker.com/engine/install/ubuntu/

Please refer to the following URL to install Repo. 

    https://source.android.com/setup/develop#installing-repo

Please refer to the following URL to understand how to download the AOSP soure.

    https://source.android.com/setup/build/downloading

Then, you can issue the following commands to donwload the Android releases for Tinker Board 2/2S.

    $ repo init -u https://github.com/TinkerBoard2-Android/manifest.git -b REVISION -m NAME.xml
    $ repo sync

Here REVISON is the manifest branch or revision (use HEAD for default) and NAME.xml is the initial manifest file.
