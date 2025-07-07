# Hashtyl 4x5+2x3

The Hashtyl keyboard is a modified version of the dactyl keyboard, focusing on ease of use, providing the right amount of keys to get the job done.

<!--toc:start-->

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Parts](#parts)
- [Building the keyboard](#building-the-keyboard)
- [Flashing the Firmware](#flashing-the-firmware)
- [Modifiying the keymap](#modifiying-the-keymap)
- [Operation Modes](#operation-modes)
- [TODO: Extra Features](#todo-extra-features)
- [Credits](#credits)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

<!--toc:end-->

## Parts

each halve of the keyboard has it's own MCU, and each halve has 6 rows and 5 columns

- Micro controllers (MCU)
  - Nice Nano v2
- Key caps
  - XDA key caps

## Building the keyboard

[Keyboard configuration](https://ryanis.cool/cosmos/beta#cm:CnsKERIFEIA/ICcSABIAEgA4MUAAChESBRCASyAnEgASABIAOB1AAAoXEgUQgFcgJxIAEgASAxCwLzgJQIDwvAIKFBIFEIBjICcSABIAEgMQsDs4CkAAChUSBRCAbyAnEgASABIAOB5AgIaKwAcYAEDohei88FVI3PCioAEKoQEKKxITEMCAAkCAgJgCSMKZoJWQvAFQQxISQICAzAJIwpmglZC8AVCGAVg6OAgKFRIQEEBAgIAgSNCVgN2Q9QNQC1CeAgonEhAQQECAgPgBSOaZ/KeQC1BXEhFAgICkA0jwmcS10DBQdFiVAVB/ChUSEECStu0MSPqZ6Ozw/AJQhgFQggIYAiIKCMgBEMgBGAAgAEDLi/yf0DFIrZHcjcGTBoIBBQKCAdcEWEhoAA==)

## Flashing the Firmware

Start by getting the firmware files from the [github repo](https://github.com/HashemRadaideh/zmk-config-hashtyl), then connect the first halve of the keyboard with a usb type-c cable to the pc, afterwards press the reset button twice to enter bootloader mode, the device should show up as a media device on your pc, simply just drag and drop the firmware file of the halve you are working on to that director, repeat for the other halve.

## Modifiying the keymap

you can easily modify the keymap using the [Keymap Editor](https://nickcoutsos.github.io/keymap-editor/) tool, edit the keys however you want then simply press save, the firmware will be rebuilt, afterwards you can grab the firmware.zip file from the latest github action, then repeat the privious step [Flashing The Firmware](#flashing-the-firmware)

## Operation Modes

- Wireless
- Wired
- Hybrid

## TODO: Extra Features

- OLED Display
- RGB
  - Underglow RGB
  - Per key RGB

## Credits

This project would've never been possible without the help of the wonderful community of the ergonomic mechanical keyboards, big thanks to the amazing people behind these projects, that helped me alot designing and making the keyboard.

- [Cosmos Keyboard Configurator](https://ryanis.cool/cosmos/)
- [ZMK Firmware](https://zmk.dev/)
- [Keymap Editor](https://nickcoutsos.github.io/keymap-editor/)
