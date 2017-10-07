#ESP8266 Envirnment Setup Procedure
##pre-reqs

Ubuntu14.04:
```
sudo apt-get install make unrar-free autoconf automake libtool gcc g++ gperf \
    flex bison texinfo gawk ncurses-dev libexpat-dev python-dev python python-serial \
    sed git unzip bash help2man wget bzip2
```
Later Debian/Ubuntu versions may require:

```
sudo apt-get install libtool-bin

```
##building

```
cd /opt
sudo git clone --recursive https://github.com/pfalcon/esp-open-sdk.git
cd /opt/esp-open-sdk
make
```
##Compile
```
export PATH=$PATH:/opt/esp-open-sdk/xtensa-lx106-elf/bin/
cd /opt/esp-open-sdk/examples/blinky
make
```

##Flash
```
sudo chown jinhao /dev/ttyUSB0
make flash
```
---
References:
[ESP-Open-SDK git link](https://github.com/pfalcon/esp-open-sdk)

[Helpful ESP8266 Blog](https://www.penninkhof.com/2015/03/esp8266-open-sdk/)

[ttyUSB0 Permission Problem](https://askubuntu.com/questions/112568/how-do-i-allow-a-non-default-user-to-use-serial-device-ttyusb0)
sudo chmod YOUR_NAME /dev/ttys0

export PATH=$PATH:/home/jinhao/esp8266/esp-open-sdk/xtensa-lx106-elf/bin/
sudo chown jinhao /dev/ttyUSB0
