# manifest

Please refer to the following URL to install Docker.

    https://docs.docker.com/engine/install/ubuntu/

Please refer to the following URL to install Repo. 

    https://source.android.com/setup/develop#installing-repo

Please refer to the following URL to understand how to download the AOSP code.

    https://source.android.com/setup/build/downloading

Then, you can issue the following commands to donwload the source for Tinker Board 2/2S Android.

    $ repo init -u https://github.com/TinkerBoard2-Android/manifest.git -b android11-rk3399 -m tinker_board_2-android11-2.0.1.xml
    $ repo sync
