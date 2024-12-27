/home/marco/.platformio/penv/bin/python" "/home/marco/.platformio/packages/tool-esptoolpy/esptool.py" --chip esp32s2 elf2image --flash_mode dio --flash_freq 80m --flash_size 4MB --elf-sha256-offset 0xb0 -o .pio/build/lolin_s2_mini/firmware.bin .pio/build/lolin_s2_mini/firmware.elf
esptool.py v4.5.1
Creating esp32s2 image...
Merged 2 ELF sections
Successfully created esp32s2 image.
<lambda>(["upload"], [".pio/build/lolin_s2_mini/firmware.bin"])
AVAILABLE: cmsis-dap, esp-bridge, esp-prog, espota, esptool, iot-bus-jtag, jlink, minimodule, olimex-arm-usb-ocd, olimex-arm-usb-ocd-h, olimex-arm-usb-tiny-h, olimex-jtag-tiny, tumpa
CURRENT: upload_protocol = esptool
BeforeUpload(["upload"], [".pio/build/lolin_s2_mini/firmware.bin"])