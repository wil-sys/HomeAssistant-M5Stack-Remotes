# HomeAssistant-M5Stack-Remotes
## This uses MQTT so make sure that your homeassistant has Mosquitto broker installed, with a username of "Remote" and a password of "Control"

Remotes for Homeassistant that use M5Stack Devices, such as M5StickC Plus, Core, and Paper (coming soon).

MQTT topics are the buttons and remote mode combined, EX ButtonA1 (ButtonA, remote mode 1).
MQTT Payloads are either true or false.
To change mode on StickC Plus press A and B simultaneously, On Core press A and C simultaneously.
