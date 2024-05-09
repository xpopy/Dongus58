# ZMK config for Lotus58 with dongle

The config allows you to use 3 nRF52840, one for the dongle, one for the left half, one for the right half. Using a dongle significantly increases battery life.

More details on the [slicemk page](https://www.slicemk.com/pages/split-dongle).

## Install

Before flashing this firmware, flash the [settings reset firmware](https://zmk.dev/docs/troubleshooting#split-keyboard-halves-unable-to-pair) into all 3 controllers. Then flash each firmware to the respective device. If the halves do not connect themselves, try pressing the reset buttons on the dongle and keyboards.

## Credit

- [@aroum](https://github.com/aroum/zmk-enki42-dongle) for the template
