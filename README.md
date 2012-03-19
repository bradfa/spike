The code to go along with an article here http://www.jumpnowtek.com

If building on Debian, using Emdebian cross compilers, instead of sourcing
the *-source-me.txt file, simply build with the following options (you'll
need to replace '../linux/' with the path to your Linux kernel, where you
have already previously built a working kernel that this module will be
inserted on):

`make KERNELDIR=../linux/ ARCH=arm CROSS_COMPILE=arm-linux-gnueabi-`
