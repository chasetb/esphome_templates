# esphome_templates
 ESPHome yaml templates for the devices I use in my home. Many of the templates were based on the sample configurations at [esphome-devices](https://www.esphome-devices.com).

## Common Files
Most devices use the same or similar microcontrollers so I'm using common files which contain the basic setup for ESPHome to run the device, setup Wi-Fi, and enable Home Assistant to talk to it. Several secrets are referenced (Wi-Fi creds, API keys, etc) which can be found in [secrets.yaml](secrets.yaml). The common files are meant to be hidden files so ESPHome doesn't think they are a separate device when placed in the same directory as the other `.yaml` files.

- ESP8266: [.common_esp8266.yaml](.common_esp8266.yaml)
- *More to come, I'm sure*