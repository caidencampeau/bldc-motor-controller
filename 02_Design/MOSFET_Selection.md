# Preliminary Rev A MOSFET: Infineon BSC066N06NS

Selected this 60V N-Channel power MOSFET for the inverter stage because of its balanced parameters:

(https://www.infineon.com/assets/row/public/documents/24/49/infineon-bsc066n06ns-datasheet-en.pdf)

VDS 60 V

RDS(on),max 6.6 mΩ

ID 64 A

QOSS 19 nC

QG(0V..10V) 17 nC



At 5 A, room-temp conduction loss is 0.165 W per conducting MOSFET before PWM, temp effects, and switching losses. The 5x6 SuperSO8 package provides good density for the PCB. Still need to test in system to make sure losses aren't too high.





