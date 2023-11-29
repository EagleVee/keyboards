# VU.A - Fully wireless split keyboard with dongle via bluetooth 5.0

<img src="images/vua_275_225.jpg" width="1024">

---

A wireless keyboard through dongle via bluetooth 5.0, powered by nRFMicro 52840, inspired by [Vincent Nguyen](https://github.com/nguyen-v)'s [Aloidia project](https://hackaday.io/project/189688-aloidia-wireless-split-solar-powered-keyboard).

I've been loving the split and alice keyboards, but they often have a critical flaw (at least for me): they use a 2.25u spacebar on the left side, and I want a longer spacebar on the left so my thumb can be comfortable both when I'm gaming and typing.

And then one day I came across the Aloidia keyboard blog from hackaday, I was immediately hooked. I took the schematic of Vincent and with the help of [Deemen17](https://github.com/Deemen17) made a lesser version, without the solar panel (I tried), but still fully wireless PLUS multi layout PCB.

Then I designed the 3D printed case; the dongle case that hold a single switch to help it enter bootloader faster, even though it probably took about 10 seconds to remove from the case and use a tweezer to shorten the pins lol.

Btw I'm a Mac user so I love my exploded Command key.

This keyboard use Geon's Tad Pole mount for simplicity.

## Video

[![Sound test](https://img.youtube.com/vi/9riWB6Ux5Mw/0.jpg)](https://youtu.be/9riWB6Ux5Mw "Give me some likes please :>")

## PCB layout support

<img src="images/vua_layout.png" width="1024">

## Resources

- [PCB v1](pcb/gerber_vua_v1.zip)
- [3D Printed Left Case](case/3d_printed_left.step)
- [3D Printed Right Case](case/3d_printed_right.step)
- [Plate Left](case/plate_left.dxf)
- [Plate Right](case/plate_right.dxf)
- [ZMK Firmware repository](https://github.com/EagleVee/zmk-config-vua)

**Disclaimer**: The PCB v1 file won't work with the current case, since we made a mistake and have the bottom of the pcb be too wide. You can still use it but you will need to trim out the bottom part of the PCBs like this, and extrude a bit of the case:

<img src="images/vua_pcb_render_v1.png" width="1024">

## Pictures

### Double 3u spacebars layout:

<img src="images/vua_3_3.jpg" width="1024">

### 3D Printed Case Images:

<img src="images/vua_case_top.png" width="1024">
<img src="images/vua_case_bottom.png" width="1024">

### Dongles:

<img src="images/vua_dongle_case.png" height="360">
<img src="images/vua_dongle.jpg" height="360">

## PCB:

<img src="images/vua_pcb.png" width="1024">

### Thanks

Special thanks to [Vincent Nguyen](https://github.com/nguyen-v) and [Deemen17](https://github.com/Deemen17) for inspired me and helped me complete this project.
