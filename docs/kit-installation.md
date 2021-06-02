## IDP Developer Kit Installation

### Vehicle Installation

1. Collect the parts of the kit required for a vehicle install.

    <img alt="Vehicle Installation Kit" src="../media/mobile-kit.png" width="75%" height="auto">

    1. Magnet mount kit
    2. ST2100 modem
    3. (Optional) extension cable(s)
    4. FieldEdge Ultralite "black box"
    5. ST2100 development cable
    6. DC automotive power adapter

2. Attach the magnet mount kit to the ST2100 using the screws provided.
You can route the cable out the long or short side using the provided channel.

    <img alt="Magnet Mount Kit" src="../media/magmount.png" width="36%" height="auto">
    <img alt="Magnet Mount installed" src="../media/magmount-installed.png" width="45%" height="auto">

3. Connect the ST2100 to either the extension cable(s) or directly to the
"black box" cable depending the total length of cable run you need.

    <img alt="Modem to cable" src="../media/modem-to-cable.png" width="45%" height="auto">

    >Note: If using for an extended period outdoors and/or to protect against
    the metal connector damaging vehicle paint, it is recommended to wrap
    the metal connection point in waterproof tape.

    <img alt="Waterproof tape" src="../media/connector-tape.png" width="31%" height="auto">
    <img alt="Taped connector" src="../media/teminal-water-scratch-resist.png" width="45%" height="auto">

4. Place the **ST2100** modem in a location with a clear view of the sky
in the direction of the Equator (e.g. south-facing in the northern hemisphere).
Ensure your cabling can run without being damaged.

    <img alt="Install location" src="../media/terminal-vehicle-roof.png" width="45%" height="auto">
    <img alt="Cable routing" src="../media/vehicle-seam.png" width="45%" height="auto">

5. Connect the **developer breakout cable** to the **Edge Ultralite** "black
box" device and the **developer breakout cable** to a power source using either
the DC automotive or AC/DC adapter cable provided

    <img alt="Breakout cable" src="../media/breakout-cable.png" width="45%" height="auto">
    <img alt="Vehicle power" src="../media/vehicle-power.png" width="45%" height="auto">

6. Using your preferred tablet/smartphone/PC, use the QR code or find and
connect to the WiFi network `isat-feu-device`.
The SSID password is: ***IsatIoT1!*** 
    
    An example using an iOS device is shown below:

    >NOTE: You can use the QR code on the device to automatically connect.

    <img alt="QR code" src="../media/wifi-qr-code.png" width="45%" height="auto">
    <img alt="iOS attach to device WiFi" src="../media/iphone-ap-connect.png" width="45%" height="auto">

> NOTE: If you cannot establish a connection to `isat-fe-device` try removing
and re-applying power to the "black box".
See [troubleshooting](#Cannot-connect-to-`isat-feu-device`-access-point).

7. Open a browser and navigate to `http://isatiot:5000`.  It should appear
similar to the following iOS/Safari example:

    >NOTE: If the `isatiot` hostname does not resolve,
    try `http://192.168.27.1:5000`

    <img alt="iOS Safari FEU Home page" src="../media/gui-main.png" width="50%" height="auto">

8. Click **IDP** to navigate to the IDP tab.  Confirm you have a connection to
the ST2100 modem.  It should appear similar to the following iOS/Safari example:

    <img alt="[iOS Safari IDP page]" src="../media/gui-idp-1.png" width="50%" height="auto">

[Back to Developer Kit Quick Start](../README.md#Getting-Started)