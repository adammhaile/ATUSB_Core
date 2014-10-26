Follow the instructions below to install ATUSB_Core

- Install Arduino IDE 1.05r2 or above.
- Download Teensy from [PJRC.com](https://www.pjrc.com/teensy/td_download.html)
- Run Teensy installer as (admin on Windows)
    -Skip driver install (unless you will actually use a Teensy)
    -Install any added libraries if desired
- Copy the ATUSB_Core folder into ```<InstallDir>/Arduino/hardware/``` or ```<UserDocs>/Arduino/hardware/```



Once firmware from this core has been uploaded to the device, you should be prompted for driver for AVR USB Serial. Point it to ./drivers/GenericSerialUSB.inf in the ATUSB_Core folder.

http://www.howtogeek.com/167723/how-to-disable-driver-signature-verification-on-64-bit-windows-8.1-so-that-you-can-install-unsigned-drivers/
