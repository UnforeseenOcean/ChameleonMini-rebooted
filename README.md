ChameleonMini-rebooted
======================

[![Build Status](https://travis-ci.org/iceman1001/ChameleonMini-rebooted.svg?branch=master)](https://travis-ci.org/iceman1001/ChameleonMini-rebooted)
[![Latest release](https://img.shields.io/github/release/iceman1001/ChameleonMini-rebooted.svg)](https://github.com/iceman1001/ChameleonMini-rebooted/releases/latest)

![Image chameleon mini revE - rebooted](http://www.icedev.se/chameleon_mini_revE/miniRevE.jpg)

# Excited news!

*This is firmware for the revised, rebooted version of the Chameleon Mini rev E which so many of you bought.
The chinese manufacturer had its firmware changes to themself which was limiting for all who bought this device.
After talks with manufacturer, they also came to the conclusion that it should be open-sourced.  I managed to get source from them and agreed to make a public repository on GitHub.
Since this firmware isn't in the official Chameleon mini repo,  I decided to make a 'iceman fork' of it.*

## Donate
https://www.patreon.com/iceman1001  Feel free to donate. All support is welcome.

monereo:  43mNJLpgBVaTvyZmX9ajcohpvVkaRy1kbZPm8tqAb7itZgfuYecgkRF36rXrKFUkwEGeZedPsASRxgv4HPBHvJwyJdyvQuP

## Notice      
Let us make this fork awesume to play with. Do please play with it. Get excited and experiment with your enhanced Chameleon Mini device!

## First Steps
-----------
This repo is focused on RevE Rebooted,    you can find useful information on [our wiki here](https://github.com/iceman1001/ChameleonMini-rebooted/wiki)

To upgrade the firmware of your ChameleonMini

For RevG owners,  
please visit the [Getting Started page](http://rawgit.com/emsec/ChameleonMini/master/Doc/Doxygen/html/Page_GettingStarted.html) from the [doxygen documentation](http://rawgit.com/emsec/ChameleonMini/master/Doc/Doxygen/html/index.html).

For RevE Rebooted owners,  
please visit the [Flashing Windows](https://github.com/iceman1001/ChameleonMini-rebooted/wiki/Flashing---windows)

## Supported Cards and Codecs
--------------------------
See [here](https://github.com/emsec/ChameleonMini/wiki/Supported-Cards-and--Codecs).

## GUI 
Based on the partial source code release for the GUI we created a new GUI.
[iceman Chameleon Mini GUI](https://github.com/iceman1001/ChameleonMini-rebootedGUI) 
It is a windows .net based software and it is really nice to work with.
Has support for Chameleon Mini revE / revG commands
and dump management,  
and color templates for dumps,
and multilanguage

Built by @bogition and @iceman1001



## Questions
---------
If you have any questions, please visit the [Issues page](https://github.com/emsec/ChameleonMini/issues) and ask your questions there so everyone benefits from the answer.


## Repository Structure
--------------------
The code repository contains
* Drivers: Chameleon drivers for Windows and Linux
* Firmware: The complete firmware including a modified Atmel DFU bootloader and LUFA
* Software: Contains a python tool for an easy configuration (and more) of the ChameleonMini, Note that this is currently under construction

## Perpetual glory!

A list of those who contributed to this repo in order to make it work. The community owns you all a deep and sincere thank you.
-  @bogiton
-  @doegox
-  @ceres-c
-  @iskuri
