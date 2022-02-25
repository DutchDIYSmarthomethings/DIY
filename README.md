# Dutch DIY Smarthome Things projects
## P1 - Slimme Meter
### DSMR2/3/4/5 Wemos version
De [`P1-Monitor.yaml`](Slimme-Meter/P1-Monitor.yaml) Is het basis bestand voor de P1-Monitor, Wilt u de gas optie gebruiken? Even out comenten. ESPHome docu kan u [hier](https://esphome.io/components/sensor/dsmr.html) vinden.

### DSMR5 ESP-01 version
De [`P1-Mini.yaml`](Slimme-Meter/P1-Mini.yaml) is het kleine broertje. Dit bestand is alleen voor de P1-Mini. (Werkt alleen met DSMR5!)

### P1 - Verwarming (Stadsverwarming / Warmtelink)
Heeft u een 'Warmtelink' P1 port voor het meten van verwarming (stadsverwarming / stadswarmte) de [`P1-Verwarming/P1-Verwarming.yaml`](Slimme-Meter/P1-Verwarming/P1-Verwarming.yaml) kunt u gebruiken.
De [`uart_read_line_sensor.h`](Slimme-Meter/P1-Verwarming/uart_read_line_sensor.h) is nodig als u de firmware wilt bouwen.

Deze print kan niet worden gebruikt voor warmtemeting met IR optische uitlezing, zoals L+G Ultraheat. Alleen recent geïnstalleerde apparaten met P1 (RJ12) poorten kunnen worden gebruikt.

## CC1101 Ventilation remotes (Itho/Duco)

### Itho ventilation remote
De [`itho.yaml`](Itho-Duco/itho.yaml) in combinatie met de CC1101 maakt het mogelijk om itho en Duco ventilatie boxen remote aan te kunenn sturen. Zo maakt uw een slimme ventilatiebox.

## Meer informatie:
Alle documentatie (installatie, setup, updates, etc.) over ESPHome kan u hier vinden https://esphome.io
