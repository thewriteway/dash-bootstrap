# bootstrap.dat files for [Dash Core](https://github.com/dashpay/dash)

Run the following commands:

linearize-hashes.py linearize.cfg > hashlist.txt (make sure DashCore is running)

linearize-data.py linearize.cfg

This code will create your bootstrap.dat

1. Place bootstrap.dat file inside of your Dash Core folder:
Windows: %APPDATA%\DashCore\
Run your wallet and let it sync using bootstrap.dat
2. Once sync is done bootstrap.dat file will be renamed to bootstrap.dat.old automagically and can be safely removed.

Credits to original author UdjinM6
