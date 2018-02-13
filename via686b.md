# VIA 686B Issues

## Introduction
In December 2000 VIA announced their new 686B Southbridge, in conjunction with the KT133A chipset. The new Southbridge differed from its predecessor by including native support for ATA100.

With the new Southbridge and KT133A motherboards, various users started experiencing data corruption problems as well as system instability when transferring files, listening to music, or anything that utilized the PCI bus. Typically, users with a KT133A chipset, 686B Southbridge and a Creative Labs Sound Blaster Live sound card were affected.

Our tests show that this problem is not limited to the SBLive!, but that systems with an Audigy soundcard can also be affected. Even worse, with an affected system, kX Drivers may not be recognized by VIA 4in1 driver package, indicating that the VIA fix may not be installed correctly.

Fixes provided by BIOS manufacturers and by VIA do not completely solve this problem. Even after solving data corruption issues you may still experience sound clicks and distortion while copying files, burning CDs, transferring data via network.

However we've found a solution that completely solves this problem. This solution consists of the following steps:
Go to your motherboard manufacturer's website and download the latest BIOS for your motherboard
Go to the VIA site and download the latest Via 4in1 drivers
Install George's PCI Latency patch (this is the only way of solving problems related to this issue in some cases)
Who needs this patch
Anyone using a 686B-based motherboard, regardless of Operation System.

## Conclusion
We recommend using George's PCI Latency version 0.19 available here or here*.
You should also install the latest VIA drivers available here and update your System BIOS. 

## References
http://www.viahardware.com/686b_1.shtm
