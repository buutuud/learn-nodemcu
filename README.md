# learn-nodemcu

##远程复制
```
scp -r user@your.server.example.com:/path/to/foo /home/user/Desktop/

scp -r yi@139.162.107.240:/home/yi/nodemcu-firmware/bin .
```

##下载固件
```
../tools/esptool.py --port /dev/ttyUSB0 write_flash 0x00000 ../bin/0x00000.bin 0x10000 ../bin/0x10000.bin

esptool.py --port COM4 write_flash 0x1000 my_app-0x01000.bin
```

##固件编译流程
```
export PATH=/home/yi/esp-open-sdk/xtensa-lx106-elf/bin:$PATH
export PATH=${PATH}:~/bin
```

##树莓派编译固件
```
export PATH=/home/yi/tools/arm-bcm2708/gcc-linaro-arm-linux-gnueabihf-raspbian-x64/bin:$PATH
```

