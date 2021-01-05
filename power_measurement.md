---
layout: page
title: Power measurement
permalink: /power_measurement.html
---
# Power measurement
Electric power (voltage and current) needs to measured in a cost-effective way.

## Current measurement
Both AC as well as DC currents can be measured using affordable integrated Hall-Effect sensors such as the [ACS712](http://www.allegromicro.com/en/Products/Current-Sensor-ICs/Zero-To-Fifty-Amp-Integrated-Conductor-Sensor-ICs/ACS712.aspx) or [similar devices](http://www.allegromicro.com/en/Products/Current-Sensor-ICs.aspx). These integrated devices can be used to measure non-fault currents up to 50A (1.2 kW at 24V) and are quick enough for active [current limiting](https://web.archive.org/web/20170429032706mp_/https://dcgrid.hackpad.com/8o5PGW8XwEC), see '[DC and Transient Current Capability/Fuse Characteristics of Surface Mount Current Sensor ICs](http://www.allegromicro.com/en/Design-Center/Technical-Documents/Hall-Effect-Sensor-IC-Publications/DC-and-Transient-Current-Capability-Fuse-Characteristics.aspx)'.

## Power measurement
Power is simply the current times the voltages, a calculation which is easily performed by any of your favorite microcontrollers, like [Arduino](https://web.archive.org/web/20170429032706mp_/https://dcgrid.hackpad.com/1WnGcfq22WV), with built-in analog to digital convertors.

Practically a no-brainer, (DC) voltage can be measured accurately using a voltage divider. For a nice example, refer to a howto on instructables [here](http://www.instructables.com/id/ARDUINO-ENERGY-METER/step3/Voltage-Measurement/).
