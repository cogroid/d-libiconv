all:
	sudo mkdir -p /home/cogroid/local/libiconv/x64
	cd ../../; \
	./configure \
	--build="x86_64-linux-gnu" \
	--host="x86_64-linux-gnu" \
	--prefix=/home/cogroid/local/libiconv/x64 \
	make

clean:
	cd ../../; \
	make clean

install:
	sudo sh -c 'cd ../../; \
	make install;'


