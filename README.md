# cod.m CP2102N USB UART

---

___Waiting for PCB's! Not yet tested!___

---

This is a reimplementation of [Watterott's CP2102N Breakout](https://learn.watterott.com/breakouts/cp2102n-breakout/) which is licensed under CC-BY-SA.
Based on Silabs CP2102N with integrated voltage regulator for the 3.3V rail.

Never did an own USB UART adapter and wanted to implement USB-C connectors. So I took this oportunity.

![cod.m CP2102N USB UART](img/codm-cp2102n-usb-uart-render.png)


## Features
* USB-C (USB 2.0) connector
* Only 0603 parts, no 0402
* RTS/DSR available as solderpads
* Bigger 3.3V/5V switch
* Power LED

## Features derived from Watterott
* 500mA Polyfuse
* TVS-Diode for USB
* TX/RX LED
* Switchable logic voltage
  * Max 450mA @ 5V, 80mA @ 3.3V
  * Input low level: <= 0.6V
  * Input high level: >= 2.7V



# Thanks
* @watterott CP2102N-Breakout https://github.com/watterott/CP2102N-Breakout
* @AislerHQ for the prototype PCB's

# License
[CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

cod.m GmbH, Patrik Mayer, 2022