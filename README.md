


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




```
