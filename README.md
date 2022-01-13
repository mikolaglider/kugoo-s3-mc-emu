# kugoo-s3-mc-emu
Kugoo s3 simple motor controller emulator for checking display controller.

## Using
Conect your UART device to kugoo s3 display controler then connect the battery supply. Don't connect your motor controller.
Add executable permissions on s3mcemu.sh file and run it with your UART device path as first parameter.

### Run example
  ./s3mcemu.sh /dev/ttyUSB0
