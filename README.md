# SD to PC Transfer Project

This project allows you to read files from an SD card using an Arduino and transfer them to a PC using Python.

## Hardware Needed

1. **USB Plug (Type A, solder type)**
[https://www.jaycar.com.au/usb-plug-type-a-solder-type/p/PP0790](https://www.jaycar.com.au/usb-plug-type-a-solder-type/p/PP0790)

2. **Arduino Compatible SD Card Interface Module**
[https://www.jaycar.com.au/arduino-compatible-sd-card-interface-module/p/XC4386?srsltid=AfmBOoqpEGeSAR6FFRhkgZUdEMexdqyawmVzsoF_6wSTULKV5bv8](https://www.jaycar.com.au/arduino-compatible-sd-card-interface-module/p/XC4386?srsltid=AfmBOoqpEGeSAR6FFRhkgZUdEMexdqyawmVzsoF_6wSTULKV5bv8)

## Instructions

1. Upload the Arduino code from `Arduino/SD_to_PC.ino` to your Arduino board.
2. Plug your Arduino into the PC.
3. Place a file named `test.txt` on the SD card.
4. Run the Python script `Python/receive_sd.py` to save the SD file to your PC.
5. 3D print the frame `3D_Print/sd_reader_frame.stl` to organize your SD module and USB cable.
