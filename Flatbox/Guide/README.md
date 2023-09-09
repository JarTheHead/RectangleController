# Flatbox Guide

Full Documentation: [https://gp2040-ce.info/#/usage](https://gp2040-ce.info/#/usage)

# Firmware Updates

1. Download the latest firmware file for the Pico Fighting Board from [https://gp2040-ce.info/#/download](https://gp2040-ce.info/#/download)
2. Unplug your controller
3. Disassemble your controller
4. Short the BOOT pins with tweezers
5. Plug in your controller to your PC while shorting the pins
6. Drag the .uf2 files to the RPI-RP2 drive that should appear
7. The controller will restart and be recognized as a controller once the update completes

# Flatbox Layout

![Flatbox Layout.svg](../Photos/Side.jpg/Flatbox_Layout.svg)

# Advanced Web Configuration

The GP2040-CE firmware has a built-in configuration app which runs locally on the controller. To access the configurator:

1. Unplug your controller
2. Hold Start while plugging in the controller to a computer
3. Open your web browser and navigate to [http://192.168.7.1](http://192.168.7.1/)
4. You can now adjust controller settings, configure RGB, reset settings, add PS4 keys, etc.

# Input Mode

Hold one of the following buttons when plugging in the controller:

- P1 - PC/XInput
- P2 - PS4
- K1 - PS3/DInput
- K2 - Nintendo Switch

# D-Pad Mode

Hold one of the following combinations while the controller is plugged in:

- Start + Select + Down - Normal d-pad (default)
- Start + Select + Left - Left analog stick
- Start + Select + Right - Right analog stick

# SOCD Mode

Hold one of the following combinations while the controller is plugged in. The SOCD mode will save after unplugging and replugging the controller

- Home + Start + Up - Up Priority (U+D = U)
- Home + Start + Down - Neutral (U+D = N)
- Home + Start + Left - Last Input Priority (outputs most recent input)

# RGB LEDs

Hold one of the following combinations while the controller is plugged in to configure RGB settings:

- Start + Select + P1 - Next Animation
- Start + Select + K1 - Previous Animation
- Start + Select + P2 - Brightness Up
- Start + Select + K2 - Brightness Down
- Start + Select + P3 - LED Parameter Up
- Start + Select + K3 - LED Parameter Down
- Start + Select + P4 - Pressed Parameter Up
- Start + Select + K4 - Pressed Parameter Down