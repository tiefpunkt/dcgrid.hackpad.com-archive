---
layout: page
title: DC appliances
permalink: /dc_appliances.html
---
# DC appliances

An overview of available DC-appliances, methods of adapting existing appliances.

## References

* [Appliances in a low-voltage DC house](https://www.google.nl/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0CCIQFjAA&url=http%3A%2F%2Fpublications.lib.chalmers.se%2Frecords%2Ffulltext%2F137511.pdf&ei=Qf91VbTKGeXP7Qah_YKYCg&usg=AFQjCNGaq-cySu_jyvI1P3nk0Z8IxMm6Zg&sig2=fb-pB1CPzGzP8QYgAmohvA&bvm=bv.95039771,d.ZGU) (Master thesis, 2011)
* [Catalog of DC Appliances and Power Systems](https://www.google.nl/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0CCEQFjAA&url=http%3A%2F%2Fefficiency.lbl.gov%2Fsites%2Fall%2Ffiles%2Fcatalog_of_dc_appliances_and_power_systems_lbnl-5364e.pdf&ei=kf91VdjxKO6N7Aanj4D4Bg&usg=AFQjCNG8ri0b7os9L2d4cot2PB7-tM3W_A&sig2=e1vxUuST2QaZY3jK4eCF3Q&bvm=bv.95039771,d.ZGU) (for U.S. DOE, 2011)

## Motorized appliances

### Dishwashers
None in existence that I'm aware of.

### Washing machines

Probably the most difficult devices, because often driven by a PWM-modulated pure-AC motor and requiring pure sines for electronics. However, some professional washing equipment exists that uses DC power (as these motors are typically variable-speed and require AC-DC-AC anyways). As an added advantage, professional machines are often have a higher effective energy- and water-efficiency because of their larger capacity and because less machines need to be built.

### Heatpump/ventilation

[Itho Daalderop](http://www.ithodaalderop.nl/) has developed an integrated heat pump/balance ventilation system working on two-fase (+/- 350 VDC). The unit is expected to hit market soon.

### Shower

The water-efficient shower produced by [Orbital Systems](http://orbital-systems.com/) might (or might not) be powered over DC. We are in the process of concacting the producers.

##  Household electronics

Most household appliances already feed on DC. Typically, the first component in their power supplies is a rectifier changing the 230 VAC to 380 VDC. From thereon a DC-DC converter takes it down to whatever voltage the device requires.


With this in mind, there are several methods for connecting them to a 24 VDC or 380 VDC outlet:

1.  Small inverter with the existing power supply. Double convertion, high loss; this should be an emergency solution.

2.  Modify the existing power supply by removing the rectifying step so it takes 380 VDC instead.

3.  Built a custom power supply or a universal (laptop) DC power supply.

4.  Integrate the power supply intirely in the house and create custom plugs for the different required voltages

5.  Use USB Power Delivery to integrate power supplies in the house and create charge cables for non-USB devices.



### Fridges
* [http://www.shop.solar-wind.co.uk/acatalog/energy_efficient_fridges_freezers_refridgerators.html](http://www.shop.solar-wind.co.uk/acatalog/energy_efficient_fridges_freezers_refridgerators.html)



## Powertools: drills, sanding machines

Battery-driven equipment essentially counts as 'household electronics' but pure powertools might be best driven by a powerful (portable) invertor. In communities, it would make sense to have one or two 'powertool' inverters in case of use of heavy machinery.

## Lighting

Fluorescent but also traditional lighting works just as well on DC. LED-lights typically last longer because there is no AC-DC conversion electronics in the device, which is typically the failing part in LED lights.

Typically, LED's require current limiting, though many modern LED's have internal current limiting and work on constant voltage drivers with 12V or 24V. Ideally, however, we would use 400 DC LED drivers such as produced by Philips for the DCC+G demonstration project. References: [_http://www.vicorpower.com/documents/whitepapers/wp_400vdc-demo.pdf_](http://www.vicorpower.com/documents/whitepapers/wp_400vdc-demo.pdf) _and_ [_http://dcgrid.tue.nl/files/2014-04-03_Boeke-DCCG_Project-Low_Voltage_DC_Power_Grids.pdf_](http://dcgrid.tue.nl/files/2014-04-03_Boeke-DCCG_Project-Low_Voltage_DC_Power_Grids.pdf)
