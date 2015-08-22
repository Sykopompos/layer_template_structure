# layer_template_structure

Just a basic structure of what we want to get together so we can create system template with the correct structure.
Once completed, we can tie things together to just change a value in one place and they will change values for M, lollipop and oem specific for max compatibility.

This is also so we can compile on device and give the user a choice of what they want and giving different options then compiling what setup they want.


just for refernce of on device compiling (with on board device aapt)

aapt package -f -M /sdcard/theme/AndroidManifest.xml -S /sdcard/theme/res/ -I /system/framework/framework-res.apk -F /sdcard/out/themename_app_overlay.apk