# Stock-Note4-Kernel

This repo will be available for anyone that would like to learn
to build there own Linux kernel for the Samsung Note 4.


# Models Available
1. SM-N910F
2. SM-N910V


# Prerequisites:

* Linux - 

    A virtual machine will work, but I prefer to dual boot Linux or have Linux as the sole OS. There are many Linux distros to pick from and if you're new to it then I recommend something like Ubuntu. Get at least Ubuntu LTS              (14.04), but you may as well get the latest version. I'm currently using Xubuntu 18.04 and it's perfect in my              opinion.

* Open terminal and install the following packages: (copy/paste)

      sudo apt-get install git ccache automake lzop bison gperf build-essential zip curl zlib1g-dev zlib1g-dev:i386 g++-multilib python-networkx libxml2-utils bzip2 libbz2-dev libbz2-1.0 libghc-bzlib-dev squashfs-tools pngcrush schedtool dpkg-dev liblz4-tool make optipng
  
* Clone source by entering the following:

      git clone https://github.com/slept-on/Stock-Note4-Kernel.git -b N910[F][V]

* Download a Toolchain- arm-eabi-4.8

    You should have a new folder named Stock-Note4-Kernel. From the terminal window you already have open enter <cd Stock-Note4-Kernel> or just open up a new terminal inside the Stock-Note4-Kernel folder. 

   To use google's prebuilt toolchain enter this:

      git clone https://android.googlesource.com/platform/prebuilts/gcc/linux-x86/arm/arm-eabi-4.8

   I prefer UberTC's prebuilt toolchain:

      git clone https://bitbucket.org/UBERTC/arm-eabi-4.8.git





#WIP
#More to Come
