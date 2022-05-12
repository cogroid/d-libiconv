all:
	sudo mkdir -p /home/cogroid/local/libiconv/i386
	cd ../../; \
	./configure \
	--build="x86_64-linux-gnu" \
	--host="i386-linux-gnu" \
	CFLAGS="-m32 -march=i386" \
	LDFLAGS="-m32 -march=i386" \
	CPPFLAGS="-m32 -march=i386" \
	--prefix=/home/cogroid/local/libiconv/i386 \
	make

clean:
	cd ../../; \
	make clean

install:
	sudo sh -c 'cd ../../; \
	make install;'


