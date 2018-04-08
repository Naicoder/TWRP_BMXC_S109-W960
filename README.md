# TWRP_S109_BMXC
device tree for S109 (W107 / W960) - 2017

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | 1.5 GHz Quad-Core MT6737T
GPU     | Mali-T720 MP2
Memory  | 2 GB RAM
Shipped Android Version | 7.0
Storage | 32 GB
Battery | 5100 mAh
Display | 10.1", 1920x1200 px
Camera  | 5MPx + 2MPx, LED Flash

================================================

To recovery build in omni sources

	$ cd ~/you_twrp_source_foldel/
    $ . build/envsetup.sh
    $ lunch omni_W960-eng
    $ make -j5 recoveryimage

## Thanks to:
 * @ipsis
 * @nemo-nemo

