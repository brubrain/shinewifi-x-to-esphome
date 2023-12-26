ESPHome integration working with HomeAssistant. 10 seconds update interval of inverter data to HomeAssistant integration.

## How to flash

- Remove the stick's PCB from the housing.
- Connect the header's Pins GPIO0 and GND with a 1k resistor. 
- Connect the stick to your pc
- Install the USB-driver for the USB-to-Serial chip if needed
- Flash ESPHome on the connected stick.
      It's also possible to flash the software on the stick with esphome webflash project: https://web.esphome.io (works best with edge browser)
- Modify the shinewifi-x.yaml with your data (xxx fields) and upload file to stick
- Remove the stick from your PC
- Remove the connection between GPIO0 and GND
- Add housing for the stick and connect it to your growatt inverter
- Add Stick as new integration to your HomeAssistant
