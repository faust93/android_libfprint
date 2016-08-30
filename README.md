LibFprint for Android [WIP]
===========================
Experimental stripped down libFprint port and FP API HAL wrapper around it.

A second chance for fingerprint authorization on custom MM ROMs.

Virtually it can be used with any device in case of ability to get raw fp sensor images.
On my current device (Meizu PRO5) I'm able to control fp sensor using character device (/dev/fpc1020)
See fpc1150.c for example of userspace sensor driver.

Since this implementation goes against Google's FP implementation guidelines use it at your own risk! :)

faust93 <monumentum@gmail.com>




