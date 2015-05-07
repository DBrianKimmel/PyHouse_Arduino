README.md
=========


This is a project folder for home automation projects involving a micro-controller and one or more sensors or controllers.

Sensors will read various things around a house or houses and report them via a lightweight wireless protocol to one or more household controllers.

Since there will potentially be a whole lot of these remote modules I have considered the following.

Arduino of various flavors.
    The Uno is fairly weak but it will suffice for many of the nodes.
    It has a very low cost going for it.
    
The base sensor module will contain:
    Some sort of micro-controller (Arduino?).
    A radio to communicate:
        Wifi via WSP8266 or
        2.4 Meshed Network or
        933Mhz Tx/Rx (Insteon?)
        433MHz Tx/Rx (Weather stations, remote fans / Lights)
    Optional Control devices:
        IR Tx/Rx to communicate with things like TV, Blueray, and other consumer devices.
        BlueTooth to allow Android (Someone else can do Apple stuff) device access.
        ENC28J60 Ethernet Shield (IPv6 compatible)
    Other software:
        IPv6 - No need to do the IPv4 thing as those addresses are already exhausted making IPv6 the only
            viable growth path.
        MQTT - to communicate the information to other controllers and nodes.
    


Modules
=======
Temperature/Humidity
WiFi
Insteon Radio
Radio Remote control (fans)
LED (RGB) Control
Pool Temperature / Salinity
BlueTooth
UltraSonic Ranger
Radio 433 MHz Rx / Tx
Radio 915 MHz Rx / Tx 
Radio 2.4 GHz Rx / Tx
IR Rx / Tx
IPv6
Pool Sensors.

