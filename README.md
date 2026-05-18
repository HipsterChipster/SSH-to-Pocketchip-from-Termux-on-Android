***Currently being redone****
This is an attempt to create, as big as possible anyway, multiple ways to flash a PocketCHIP as those of us who have had one are as devoted to it as the devil on coke night at the millennial "git some" week long punani drilling event at punani-hub in the outer rim. Tickets not for sale and invite by Satan himself. And for those who dont have game, make sure you bring some lube to get whichever girl(s) you end up with nice and sloppy wet in the event she is bored and/or OD'd and your trying to hurry and bust one off. Be there or be Pi's extra dimension. Or even just square. 

Hail PocketCHIP!
We...we love you PocketCHIP!

This is for Linux OS's acting as the system intended to flash from, such as Ubuntu, Debian, Kali, Fedora, etc.
Not sure about Windows or Apple because they are not my bag, so if your looking for that then fuck off can't!
 First off- we have to have all the apt's required to be able to pull this off and so here we are-
make gcc gcc-arm-linux-gnueabihf libusb-1.0-0-dev 
There is one that you'll need to use that from everything I've ever tried or seen, you'll have to use this one version of sunxi-tools and not the one in your local package manager. 

git clone https://github.com/linux-sunxi/sunxi-tools v1.3

cd into the sunxi-tools directory and type:
make
make target-tools
make install-misc
make install-all
check for error messages and if none then your good here. 
