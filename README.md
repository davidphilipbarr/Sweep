# Sweep

## What is sweep?

Sweep is a version of the more fabulous [Ferris](https://github.com/pierrechevalier83/ferris) by [Pierre Chevalier](https://github.com/pierrechevalier83/) that uses a daughter board like a promicro, elite-c, bit-c, nice!nano etc. instead of using onboard components.

## What are the different types?

There's only choc version of Sweeps, unlike the Ferris, which offers many different versions for different switch types. 

* Sweep2 - this superceeds the compact and possibly the compact ble, it is compact with power switches and puck support.
* Sweep Compact - this is based on the Ferris compact.
* Sweep Compact Low - this uses pg1232 or 'choc minis' rather than the standard choc v1 switch.
* Sweep Compact BLE - basically the compact, with the trrs removed and reversable controller footprint.
* Sweep34 - this was the OG Sweep, before there was a choc spaced Ferris, I consider it retired now, and would use the Sweep Compact.

## Firmware

The firmware can be found with the Ferris firmware as part of QMK. 

Firmware for zmk and bluemicro_ble is called "Cradio".



## BOM

To build a Sweep you will need:

* 2x promicro compatible boards or 2 nice!nanos.
* Sweep 2 controllers face down. 
* 34 choc switches
* 2x reset switches (optional)
* Some little rubber feet/bumpers
* Optional for sweep 2 2x power switches (MSK 12C02)
* **Important:**  On the Sweep Compact *left* half of the Sweep the promicro's USB port must face *towards* the PCB, and on the *right* half the USB port must face *away* from the PCB (so that the promicro's components are visible).

## Who made this?

* Pierre Chevalier
* David Barr
* [Ibnu Daru Aji](https://github.com/ibnuda/)
