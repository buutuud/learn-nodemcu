# learn-nodemcu

##远程复制
scp -r user@your.server.example.com:/path/to/foo /home/user/Desktop/

scp -r yi@139.162.107.240:/home/yi/nodemcu-firmware/bin .
##下载固件
../tools/esptool.py --port /dev/ttyUSB0 write_flash 0x00000 ../bin/0x00000.bin 0x10000 ../bin/0x10000.bin
