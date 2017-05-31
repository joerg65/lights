Android lights HAL driver for backlight control on Odroid C1/2 boards

To compile the library this sourcecode must be merged into the Android source at hardware/libhardware/modules/lights.
The do a "mmm hardware/libhardware/modules/lights".
It will be compiled into out/target/product/odroidc/obj/lib/lights.odroidc.so.
To copy to Odroid C1: "adb push out/target/product/odroidc/obj/lib/lights.odroidc.so /system/lib/hw/"
And then do reboot.
The pwm at pin 33 does vary with the brightness slider.



