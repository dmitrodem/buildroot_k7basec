# About #

External tree for [buildroot](https://buildroot.org/). Used together with `K7 Base C` FPGA board.

Clone `buildroot` and run the following command to configure it:
```
make BR2_EXTERNAL=<point-here> microblaze_k7basec_defconfig
```
