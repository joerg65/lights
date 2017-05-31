Android lights HAL driver for backlight control on Odroid C1/2 boards

To compile the library this sourcecode must be merged into the Android source at hardware/libhardware/modules/lights.<br /><br />
Then do a "mmm hardware/libhardware/modules/lights".<br /><br />
It will be compiled into out/target/product/odroidc/obj/lib/lights.odroidc.so.<br /><br />
To copy to Odroid C1: "adb push out/target/product/odroidc/obj/lib/lights.odroidc.so /system/lib/hw/".<br /><br />
And then do reboot.<br /><br />
The pwm at pin 33 does vary with the brightness slider.



