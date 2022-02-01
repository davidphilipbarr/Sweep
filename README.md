# Sweep

![](/gallery/sweep2-splash.jpg)

<span>
  <a href="https://discord.gg/czXcTXbsgU">
    <img src="https://discordapp.com/api/guilds/669011382284451861/widget.png?style=shield">
  </a>
  <img src="https://img.shields.io/github/last-commit/davidphilipbarr/sweep">
</span>

## What is sweep?

Sweep is a version of the more fabulous [Ferris](https://github.com/pierrechevalier83/ferris) by [Pierre Chevalier](https://github.com/pierrechevalier83/) that uses a daughter board like a promicro, elite-c, bit-c, nice!nano etc. instead of using onboard components.

## What are the different types?

| Device | Bluetooth Support<sup>[1]</sup> | On/Off Switch | Reversible PCB | Choc V1 | Choc V2 | Choc Mini | MX & Alps | Choc Spacing<sup>[2]</sup> | Tenting<sup>[3]</sup> |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Sweep2.x          | ✔ | ✔ |   | ✔ |   |   |   | ✔ | ✔ |
| Sweep Bling MX    | ✔ | ✔ | ✔ |   |   |   | ⚠<sup>[4]</sup> |   | ✔ |
| Sweep High        | ✔ | ✔ |   | ✔ | ✔ |   | ✔ |   | ✔ |
| Sweep Half Swept  | ✔ | ✔ | ✔ | ✔ |   |   |   | ✔ | ✔ |
| Sweep Compact Low | ✔ |   | ✔ |   |   | ✔ |   | ✔ |   |

*<sup>[1]</sup> It simply means that it supports the nice!nano. An on/off switch is recommended for bluetooth*  
*<sup>[2]</sup> Choc spaced boards have the switches in a tighter grid. This provides a better final look but is only compatible with some choc keycaps (e.g. MBK)*  
*<sup>[3]</sup> Supports splitkb's [tenting puck](https://splitkb.com/products/tenting-puck?_pos=1&_psq=tenting%20&_ss=e&_v=1.0)*  
*<sup>[4]</sup> MX + kailh hotswap ONLY. Alps are NOT supported*  


* Sweep2 - Recommended Choc v1 board with all the features.
* Sweep Bling MX - An MX only Sweep that features Kailh's hotswap sockets and a stacked case.
* Sweep High - Same as the Sweep2 but trades choc spacing for compatibility with more switches and keycaps.
* Sweep Half Swept - Half of a Sweep2 with double pro-micro footprint (letting you avoid having one daughter-board flipped upside-down)
* Sweep Compact Low - The only version that supports Choc minis.

## Components list

To build and use a Sweep you will need:

* 1x PCB Kit
* 2x promicro compatible boards or 2 nice!nanos.
* 34 switches of a compatible type (refer to the compatibility table)
* 34 keycaps
* 2x reset switches (optional; [B3U-1000P(M)](https://github.com/davidphilipbarr/Sweep/issues/20))
* Some little rubber feet/bumpers
* 2x power switches (optional if supported; MSK 12C02)
* 1x TRRS (not TRS!) cable (wired build only)
* 2x TRRS Jack [PJ-320A] (wired build only)
* 1 USB Cable (depends on your micro-controller choice)

## How do I make this thing?

<a href="https://www.youtube.com/watch?v=fBPu7AyDtkM" target="_blank">
  <img src="https://gist.githubusercontent.com/duckyb/337340baa1f0c8bcc06fef7b3b57242b/raw/97e6e0748dd1b8a3fb54fac0a88e84e6b6e0e10a/build-guide-button.svg" height="44">
</a>

## Firmware

The firmware can be found [with the Ferris  firmware as part of QMK](https://github.com/qmk/qmk_firmware/tree/master/keyboards/ferris/sweep).

Firmware for zmk and bluemicro_ble is called ["Cradio"](https://zmk.dev/docs/hardware/).

## Keyboard Layout

Here is the link to the Sweep layout for the [Keyboard Layout Editor](http://www.keyboard-layout-editor.com/#/gists/c921f16f09124939db46fc301bf06096).

Default is [Miryoku](https://github.com/manna-harbour/miryoku) inspired, the default is there to be replaced. You could use this as a base to create and save your own layout version.

## Who made this?

* [Pierre Chevalier](https://github.com/pierrechevalier83)
* [David Barr](https://github.com/davidphilipbarr)
* [Ibnu Daru Aji](https://github.com/ibnuda/)
* [Duccio](https://github.com/duckyb)

