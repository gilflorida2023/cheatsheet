# cheatsheet
## clipboard
### copy file to clipboard
	xclip -selection clipboard < /path/to/file  
## git
### add git tag and version label
	git tag -a v1.0.0 -m "Version 1.0.0 - Initial release"
	git push origin v1.0.0
 ### delete version tag and version label fro remote repository
 	git tag -d v1.0.0
	git push --delete origin v1.0.0

 ## gnu build
 ### setup make
	autoheader
	autoconf
	automake
	automake --add-missing
	./configure
	make
 ### debug options 
	./configure --enable-debug
	make
### release options
	./configure --disable-debug CFLAGS="-O2"
	make
## cmake build
	mkdir build
	cd build
	cmake .. -DCMAKE_BUILD_TYPE=Debug
	make
 # ssh
 ### ssh tunnel for remmina
	ssh -L 5901:localhost:5900 remote_username@remote_ssh_server

 # swap
 ### stop swap
	sudo swapoff -a
### Turn swap on
	sudo swapon -a





