<p align="center"><img src="../../images/logo.png" height="250" alt="LeaderOS's logo" /></p>

<h1 align="center">LeaderOS 3D Printer Firmware</h1>

<hr>

## LeaderOS

LeaderOS is a project based on the [Marlin](https://github.com/MarlinFirmware/Marlin) 3D Printer Firmware, created by @LeadOn and @Twixer originally for their Ender 3 v2. First, the idea was to build their own firmware for fun, and adding cool features in it. But, one day, @Twixer bought an Wanhao D12, and saw the aweful experience of not having an official firmware made by the company, but was developed by someone random in their community. But what's wrong about that you might say? Well, having closed source firmware is not cool at all, and this is why this project exists. Everyone should be in control of what's installed on their machine, especially if it's connected to the internet.

## Ender 3 v2 - CR Touch

This branch is dedicated for the Ender 3 v2, with an official CR Touch installed on it. Everything else is stock on the printer.

## Features

Here are all features present in this firmware :

- Based on Marlin 2.1.2.1
- Using MarlinUI for UBL
- CR/BL Touch support (NOZZLE_TO_PROBE offset is set according to Creality's Ender 3 v2 Stock mounting bracket)
- Multiplied probe speed
- Unified Bed Leveling
- Added Z Offset Wizard
- Added M73 G-Code (set current percentage)
- Enabled Babystepping
- S-Curve Acceleration enabled to reduce vibrations on stepper motors
- Bed Leveling and Tramming menus added, for manual and automatic leveling
- Added Host Action Commands and Host Prompt support to have full OctoPrint usages
- Many more!

## Building LeaderOS

In order to build LeaderOS, please follow official Marlin's documentation (here built using VS Code/PlatformIO). Here, every setting is ready for a stock Ender 3 v2, with CR Touch Added, and a Creality 4.2.2 motherboard. You just need to run PlatformIO or Auto Build Marlin to build it.

## Changelog

| Version                              | Release date | What's new                 |
| ------------------------------------ | ------------ | -------------------------- |
| [2.1.2.1](https://valentinvirot.fr/) | 6/12/2023    | Updated to Marlin 2.1.2.1. |
| [2.1.2](https://valentinvirot.fr/)   | 12/26/2022   | Updated to Marlin 2.1.2.   |
| [1.0](https://valentinvirot.fr/)     | 11/16/2022   | First release.             |
