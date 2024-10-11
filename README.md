BLE NUS CLIENT
=============================

This smartBASIC application runs on a BL654-US usb dongle to act as a Nordic
Semicondutor's BLE UART service client.

When plugged into a PC the USB dongle will appear as a COMport to which AT
commands can be sent to perform actions as per the pdf file in this repo.

To look for BLE devices, scan for adverts using the command

AT+LSCN

Once you know the address of teh device that is has the NUS server then
connect to it using the command

ATDaaaaaaaaaaaa

Where aaaaaaaaaaaa is the bluetooth address of the device.
If connection happens then you will see a message CONNECT ....
If connection does not happen then you will a message NOCARRIER

For more details look at the pdf.