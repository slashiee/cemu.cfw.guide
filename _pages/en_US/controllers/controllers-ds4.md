{% include toc title="Table of Contents" %}

## Downloads

- The latest release of [DS4Windows](https://ryochan7.github.io/ds4windows-site/)
- The latest release of [Cemuhook](https://cemuhook.sshnuke.net/)
    - If you installed Cemuhook earlier, you don't need to download this

## Instructions

1. Download and extract DS4Windows to your computer
  - Select the `_x64.zip` file
1. Connect your Dualshock 4 controller to Windows via Bluetooth
1. Open the DS4Windows application
1. Ensure your controller is registered with DS4Windows
1. Navigate to the `Settings` tab
1. Enable `Hide DS4 Controller`
1. Enable `UDP Server`
  - This should say `127.0.0.1` with port `26760`

    ![]({{ "/assets/images/ds4windows.png" | absolute_url }})
    {: .notice--info}

1. Open the Cemu application
1. On the top bar, go to `Settings` -> `Input settings`
1. Change `Emulate controller` to `Wii U Gamepad`
1. Change `Controller API` to `XInput`
1. Change `Controller` to `Controller X`
1. Proceed to map all your controller button inputs
1. At the top, enter in a controller profile name, e.g. `DS4 Controller`
1. Click `Save`

## Motion Controls

1. On the top bar, go to `Settings` -> `Gamepad Motion Source`
1. Select your controller from this list
1. Select `By slot`
