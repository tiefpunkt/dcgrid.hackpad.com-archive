---
layout: page
title: Energy Router
permalink: /energy_router.html
---
# Energy Router

Modular component grouped around an [Arduino](https://web.archive.org/web/20170429032709mp_/https://dcgrid.hackpad.com/1WnGcfq22WV)(-compatible) micocontroller performing switching, measurement and accounting for electrical power.

## Initial functionality

*  'Black boxed' DC/DC converters (safety and overall project simplicity)
* [Arduino](https://web.archive.org/web/20170429032709/https://dcgrid.hackpad.com/1WnGcfq22WV#Arduino-) microcontrollers for switching, managing and measuring power flow
* Preferably wired internet connection for data logging and centralized control* Power delivery and switching functionality should be independent of internet connectivity
* [Power measurement](https://web.archive.org/web/20170429032709/https://dcgrid.hackpad.com/g41ef9Dty5f#Power-measurement-) and [current limiting](https://web.archive.org/web/20170429032709/https://dcgrid.hackpad.com/8o5PGW8XwEC#current-limiting) per interconnect

## Advanced functionality

In a later stage, the energy router might be updated to perform integrated control of:
* Charging batteries, based on [ARDUINO MPPT SOLAR CHARGE CONTROLLER](https://web.archive.org/web/20170429032709/http://www.instructables.com/id/ARDUINO-SOLAR-CHARGE-CONTROLLER-Version-30/)
* DC/DC conversion from/to the grid as well as internally
* Conversion to 230 VAC from the grid's 300 VDC or the internal 24 VDC
