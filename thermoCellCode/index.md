# thermoCellCode

## Thermocell

Andrey Gunawan won a grant from the Electrochemical Society (ECS) to
demonstrate his thermogalvanic cell for heat recovery in
automotive applications. So we designed an apparatus to simulate
conditions in an automotive application including:

* Variable ambient temperature and flow using a room air conditioner and exhaust fan blowing through a small wind tunnel
* Variable temperature engine exhaust using a heat gun
* Removable thermocell
* Measurement of temperatures throughout the thermal network
* I-V curve tracing

To collect data we used these instruments and modifications.

Instruments and controls
* Campbell Scientific CR23x for temperature recording. We programmed the
  instrument with the proprietary software, then polled it like a DAQ using
  the serial connection and interface manual. This provided data at about
  1 sec intervals instead of the 60 second intervals for logged data.
* Keithley .... We used the source-current, read-voltage function to 
  perform current sweeping, potentially for MPPT with the low-current cell.
* Arduino board for control. We controlled the room A/C via its infrared
  receiver. We also added relays to switch the heat gun and blower fan.
  
To-Do:
* Connect above bullet points to code sources
* Include images, schematics, and protocols
* References for publications
