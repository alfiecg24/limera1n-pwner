<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=48E223&width=435&lines=limera1n+pwner;For+iPod+touch+(3rd+gen),+iPhone+3GS,;And+all+A4+based+devices;Compatible+with+M1+and+Intel+Macs" alt="limera1n pwner, for M1 and Intel Macs" /></a>

# limera1n-pwner
A limera1n pwner for the iPod touch (3rd generation), the iPhone 3GS and all A4-based devices.

# Compatibility

* M1 and Intel Macs: macOS Monterey or higher (need libusb bottles for lower versions)
* Could easily be modified for Linux but I don't have a machine to test it

# Features

* Fully functioning limera1n pwner, written completely in Python
* Put a supported device into pwned DFU mode
* Fix for PyUSB having no backend
* Support for macOS Monterey and higher

# Notes

Make sure to have both PyUSB and libusb installed

```pip3 install pyusb```
```brew install libusb```

# Credits

* Majority of the code taken from axi0mx's [ipwndfu](https://github.com/axi0mx/ipwndfu)
* I have ported it to Python 3
* I have fixed the libusb errors
* I have fixed other errors that occur in ipwndfu on the latest macOS versions
