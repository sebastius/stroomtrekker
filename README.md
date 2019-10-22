# stroomtrekker
Clone of Pwuts' MeterTrekker. Stroomtrekker/MeterTrekker is a tiny circuit to read the status of your power consumption meter via the P1 port. Both our versions should be able to power an ESP8266/32 via the P1 port, so no extra cables required! You can then use the microcontroller to publish the acquired data over MQTT or any other protocol, should you choose to write software for it ;)

Boards have *just* been ordered, so make these at your own risk.

![Stroomtrekker PCB layout](stroomtrekker.png)

## BOM
### Semiconductors
* 1x Wemos D1 mini or ESP32 D1 mini
* 1x 2N7002 mosfet (or any generic SOT23 mosfet will probably work)

### Resistors
(all 0805 size)
* 1x 470R
* 1x 2K4
* 1x 4K8

### Capacitors
* 1x 470uF 6.3V

### Connectors and cables
* 1x RJ12 connector
* 1x RJ12 cable
