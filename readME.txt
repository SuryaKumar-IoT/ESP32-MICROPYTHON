how to install

git clone https://github.com/espressif/esptool.git
$ cd esptool
$ pip install --user -e .


set path in system environment variable

goto install folder copy the path

paste in system variable path

1.Erase Previous Flash in ESp32

esptool --port COM port Number erase_flash

2.Write New FirmWare IN to esp32

download new firmware

esptool.py --port COM4 write_flash 0x1000 esp32-idf3-20200902-v1.13.bin

3.Program Esp32 using MicroPython
 