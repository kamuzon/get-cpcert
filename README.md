# get-cpcert
Console utility to convert cryptopro4 and cryptopro5 certificate (gost-2001, gost-2012) into pem file for openssl 1.1.1

## build
<pre>
Tested on ubuntu 20.04 LTS 64bit

prepare.sh -- download,build & install openssl 1.1.1 & gost-engine + cmake
  it takes about 530Mb disk space and 20min to build on my notebook
  (365Mb cmake, 127Mb openssl, 6.8Mb engine)

**Modifies openssl on the system library path.**

build.sh -- build get-cpcert
  it outputs get-cpcert and libgost.so
</pre>

## usage
<pre>
get-cpcert folder.000 password > certificate.pem
</pre>

## prebuild binaries
<pre>
get-cpcert-bin.tar.gz -- contains prebuild binaries for ubuntu 14.04 64bit and 3 samples for testing
</pre>
  
