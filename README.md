Getting Started
---------------

To get started with PAC in Black, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the PAC in Black trees, use a command like this:

    repo init -u git://github.com/PACinBlack/android.git -b cm-10.1

To sync up:

    repo sync

Then to build:

    ./build-pib.sh <device_name>
    example: ./build-pib.sh urushi
