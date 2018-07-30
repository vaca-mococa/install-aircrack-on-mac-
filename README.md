# install-aircrack-on-mac-
 wget http://download.aircrack-ng.org/aircrack-ng-1.2.tar.gz
 tar -zxvf aircrack-ng-1.2.tar.gz
 cd aircrack-ng-1.2
 autoreconf -i
 ./configure --with-experimental
 make
 make install
