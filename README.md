# Rxvt-unicode prepared to compile with perl extensions 

## Dependencies

apt-get install build-essential

apt-get install libperl-dev

apt-get install libx11-dev

apt-get install libxft-dev 


## Compile 

./configure --prefix=/usr/local/ --disable-pixbuf --disable-startup-notification

make

make install
