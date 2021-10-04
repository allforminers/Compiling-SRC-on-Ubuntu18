


```
Compiled OLD src u18

sudo apt-get remove libssl-dev
sudo apt install libssl1.0-dev

make clean -f makefile.unix

cd src/leveldb
chmod +x build_detect_platform
make clean
make libleveldb.a libmemenv.a
cd ..
make -j8 -f makefile.unix 



git clean -dxf
make clean
chmod 777 ./autogen.sh
chmod 777 ./configure
chmod 777 ./share/genbuild.sh
chmod 777 ./src/secp256k1/autogen.sh
chmod 777 ./src/leveldb/build_detect_platform

./autogen.sh
./configure --disable-tests --disable-bench --without-gui --with-unsupported-ssl
make -j8


git clean -dxf
make clean
chmod 777 ./autogen.sh
chmod 777 ./configure
chmod 777 ./share/genbuild.sh
chmod 777 ./src/secp256k1/autogen.sh
chmod 777 ./src/leveldb/build_detect_platform

./autogen.sh
./configure --disable-tests --disable-bench --without-gui
make -j36



./configure --disable-bench --without-gui --disable-tests --with-incompatible-bdb --without-miniupnpc --disable-zmq --enable-shared --disable-asm --with-unsupported-ssl
make -j6



--with-unsupported-ssl
apt-get install libssl1.0-dev 
quark
autoreconf -f -i && .configure

sudo sh ./autogen.sh
./configure
make -j6 && make install

libtoolize --force
aclocal
autoheader
automake --force-missing --add-missing
autoconf
./configure
```
