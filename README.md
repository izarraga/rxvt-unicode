# rxvt-unicode

apt-get install build-essential
apt-get install libperl-dev
apt-get install libx11-dev
apt-get install libxft-dev

./configure --prefix=/usr/local/ --disable-pixbuf --disable-mousewheel --disable-startup-notification
make
make install
