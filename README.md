# SQTD-B39-4K-Trinocular-Microscope-Camera-Firmware-Dump
SQTD-B39 4K Trinocular Microscope Camera Firmware Dump


Hi, in this repository, I will dump the flash memory for the SQTD-B39 microscope in case of firmware failure.


# Microscope image

<p align="center">
  <img width="100%" height="80%" src="./Pictures/sqtd-b39-4k-trinocular-microscope-camera-ultra-hd-industrial-level-ccd-digital-detector-large.jpg">
</p>

# Photo for the flash memory

<p align="center">
  <img width="100%" height="80%" src="./Pictures/Flash.jpg">
</p>

# Dumping Process
From the image above. We got the flash memory information:
* Part Number: W25N01GVZEIG
* Type: NAND FLASH.
* SIZE: 1 Gbit.
* Voltage: 3 V.

I have used the XGCEU T48 with the WSON-8-to-DIP-8 socket. Please kindly note that the flash memory

Socket Used:
<p align="center">
  <img width="100%" height="80%" src="./Pictures/Socket.jpg">
</p>

The following picture shows the socket connected to the programmer.
<p align="center">
  <img width="100%" height="80%" src="./Pictures/P_20230528_225346.jpg">
</p>

Dumping Process:
<p align="center">
  <img width="100%" height="80%" src="./Pictures/2023-05-28 22_50_37-Xgpro v12.57.png">
</p>

# Dumped files
Kindly see the folder [Dump](./Dump).