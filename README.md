# GIMX Configuration for PG-9023S Controller

Configuration to use a PG-9023S Bluetooth controller with GIMX. This was tested
on a Linux mint computer and PS3 using a DIY USB adapter. This configuration is
a direct mapping to the original PS3 buttons.

## Getting Started

To use this, you will need to have GIMX installed and operational on your computer.
Additionally, you will need the PG-9023S Bluetooth controller in Android HID 
Mode and paired with your computer. To do this, press and hold *Home* and *X* 
on the controller until the *search* LED starts blinking rapidly, then pair 
with your computer. When it is succesfully connected, the *search* LED will be 
on solid.

## Installing

Download these files and put in your local gimx configuration directory.

## Additional Info

Because this controller does not have an extra button to serve as the PS button,
the pause button was used instead. The audio controlls are seen as a keyboard
by the computer. GIMX disabled the controller if any keyboard inputs were used
in the configuration, so I had to use a macro as a workaround. The PS button
was tied to button 2 on the controller (which does not exist), and the macro
ties the pause button to button 2.

The PG-9023S controller can be found on [Ebay](https://www.ebay.com/sch/117042/i.html?_nkw=pg-9023S)

## Authors

* ** Joe Rothrock** - *Initial Work* - [akmjoe](https://github.com/akmjoe)



