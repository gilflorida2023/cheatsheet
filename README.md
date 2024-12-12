# cheatsheet
## git
### add git tag and version label
	git tag -a v1.0.0 -m "Version 1.0.0 - Initial release"
	git push origin v1.0.0
## compile with configure
### debug options 
	./configure --enable-debug
	make
### release options
	./configure --disable-debug CFLAGS="-O2"
	make

 ## gnu build
 ### setup make
	autoheader
	autoconf
	automake
	automake --add-missing
	./configure
	make


