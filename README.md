![ImprovementUI](banner.png)

# Improvement UI for macOS Mojave and Catalina.
(only to Unsupported Macs)


# What is this?

A cosmetic improvement for the windows and popovers corners (and shadows) that has been updated to the API Metal.  

# Notes

The mask for the corners of the FrameViews has been updated to Metal API. Therefore, the corners will not be perfectly rounded after applying this correction. But the visual experience will be much more pleasant.

If the application cannot be opened because it is from an unidentified developer: System Preferences> Security and Privacy> General and allow the application to run 


This utility is provided to anyone free of charge.

# More
If Catalina 10.15.4 or later stuck on boot screen:

Disable SIP.
1. Reboot your Mac into install disk 
2. Click Utilities > Terminal.
3. In the Terminal window, type in: csrutil disable and press Enter.

Disable AMFI

4. In the Terminal window, type in: nvram boot-args="-no_compat_check amfi_get_out_of_my_way=0x1" (with quotes) and press Enter
5. Restart your Mac.

# How to use and additional info
[Readme](https://github.com/fabioiop/ImprovementUI/blob/master/Readme.pdf)


# Download
[Download link](https://github.com/fabioiop/ImprovementUI/releases/)
