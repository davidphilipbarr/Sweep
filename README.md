# Sweep
<!--
           ___                        ___
      ___ |   | ___ ___      ___ ___ |   | ___
 ___ |   |`___`|   |   |    |   |   |`___`|   | ___
|   |`___`|   |`___`___`    `___`___`|   |`___`|   |
`___`|   |`___`|   |   |    |   |   |`___`|   |`___`
|   |`___`|   |`___`___`    `___`___`|   |`___`|   |
`___`|   |`___`|   |   |    |   |   |`___`|   |`___`
|   |`___`     `___`___`    `___`___`     `___`|   |
`___`           ___ ___      ___ ___           `___`
               |   |   |    |   |   |
               `___`___`    `___`___`
-->
>  ![sweep-hero](https://github.com/davidphilipbarr/Sweep/assets/27895007/97e13cdc-b84b-4545-8e09-139a4bb935e5)  
> <sub>Bluetooth Sweep 2 + MBK Legend Keycaps</sub>

<span>
  <a href="https://discord.gg/czXcTXbsgU">
    <img src="https://discordapp.com/api/guilds/669011382284451861/widget.png?style=shield">
  </a>
  <img src="https://img.shields.io/github/last-commit/davidphilipbarr/sweep">
  <img src="https://img.shields.io/github/v/release/davidphilipbarr/sweep?include_prereleases&color=success">
  <img src="https://img.shields.io/static/v1?label=license&message=SHL-2.1&color=success">
</span>

## What is sweep?

Sweep is a version of the more fabulous [Ferris](https://github.com/pierrechevalier83/ferris) by [Pierre Chevalier](https://github.com/pierrechevalier83/) that uses a daughter board like a promicro, elite-c, bit-c, nice!nano etc. instead of using onboard components.

## What are the different types?

⭐ Sweep 2 - Recommended Choc v1 board with all the features.  
⭕ Sweep Half Swept - Same as Sweep 2, but with a reversible pro-micro footprint.  
⭕ Sweep Bling MX - An MX only Sweep that features Kailh's hotswap sockets and a stacked case.  
⭕ Sweep Bling LP - A Choc v1 only Sweep that features Kailh's hotswap sockets.  
⭕ Sweep High - Same as the Sweep 2, but trades choc spacing for compatibility with more switches and keycaps.  
⭕ Sweep High M - A soldered MX only Sweep, with a reversible PCB design.  
⭕ Sweep Mini - The only version that supports Choc minis.  

| Device | On/Off Switch<sup>[1]</sup> | Reversible PCB<sup>[2]</sup> | Choc V1 | Choc V2 | Choc Mini | MX & Alps | Choc Spacing<sup>[3]</sup> | Tenting<sup>[4]</sup> | Hot Swap |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Sweep2.x          | ✔ |   | ✔ |   |   |   | ✔ | ✔ | Mill-Max (optional) |
| Sweep Bling LP    | ✔ |   | ✔ |   |   |   | ✔ | ✔ | Kailh (required) |
| Sweep Bling MX    | ✔ | ✔ |   |   |   | ⚠<br/><sup>[5]</sup> |   | ✔ | Kailh (required) |
| Sweep High        | ✔ |   | ✔ | ✔ |   | ✔ |   | ✔ |
| Sweep High M      | ✔ | ✔ |   |   |   | MX |   | ✔ |   |
| Sweep Half Swept  | ✔ | ✔ | ✔ |   |   |   | ✔ | ✔ | Mill-Max (optional) |
| Sweep Mini        |   | ✔ |   |   | ✔ |   | ✔ |   |

> Note: All versions support bluetooth with Nice!Nano

*<sup>[1]</sup> An on/off switch is recommended for bluetooth builds.*  
*<sup>[2]</sup> With a reversible PCB it's easier to make mistakes during assembly, but it allows you to purchase less boards.*  
*<sup>[3]</sup> Choc spaced boards have the switches in a tighter grid. This provides a better final look but is only compatible with some choc keycaps. (e.g. MBK)*  
*<sup>[4]</sup> Supports splitkb's [tenting puck.](https://splitkb.com/products/tenting-puck?_pos=1&_psq=tenting%20&_ss=e&_v=1.0)*  
*<sup>[5]</sup> MX + kailh hotswap ONLY. Alps are NOT supported.*  

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

## Who made this?

* [Pierre Chevalier](https://github.com/pierrechevalier83)
* [David Barr](https://github.com/davidphilipbarr)
* [Ibnu Daru Aji](https://github.com/ibnuda/)
* [Duccio](https://github.com/duckyb)
