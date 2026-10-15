\# Preliminary Gate Driver Selection: Texas Instruments DRV8323S



\## System Requirements

* DC bus : 12-24 V
* Three half bridges / six N-channel MOSFETs
* Hall-sensored six-step commutation 
* STM32 3.3V logic
* Three-shunt current sensing for each phase
* SPI config



Thus I chose the device below to match all requirements for implementation on the board:



\*\*Texas Instruments DRV8323S\*\*

(https://www.ti.com/lit/ds/symlink/drv8323.pdf?ts=1791971296279)

Page 28 provides useful functional block diagram.



This provides the best balance of voltage capability, protection, and design complexity for this project.

