# Android Firmware Flashing Guide

## Overview
This guide provides instructions on how to flash multiple image files to your Android device using Fastboot mode. Ensure you have all necessary files and tools before proceeding.

## Prerequisites

1. **Fastboot Tools**: Ensure that Fastboot tools are installed on your computer.
2. **Drivers**: Install the correct drivers for your device.
3. **Image Files**: Ensure you have the correct and compatible image files.

## Flashing Procedure

### Boot Your Device into Fastboot Mode

1. Power off your device.
2. Press and hold the Volume Down and Power buttons together until the device boots into Fastboot mode. (The method to enter Fastboot mode may vary by device.)

### Open Fastboot Command Prompt/Terminal on Your Computer

1. Open Command Prompt (Windows) or Terminal (Linux/Mac) on your computer.

### Use the Following Commands

Replace the file names with the correct ones for your device if they differ:

```bash
fastboot flash boot boot.img
fastboot flash boot_debug boot-debug.img
fastboot flash cache cache.img
fastboot flash dtbo dtbo-verified.img
fastboot flash lk lk-verified.img
fastboot flash md1img md1img-verified.img
fastboot flash recovery recovery.img
fastboot flash scp scp-verified.img
fastboot flash spmfw spmfw-verified.img
fastboot flash sspm sspm-verified.img
fastboot flash tee tee-verified.img
fastboot flash userdata userdata.img
fastboot flash vbmeta vbmeta.img
fastboot flash vbmeta_vendor vbmeta_vendor.img
fastboot flash super super.img



