\# Hardware Design



\## Rev A Status



\### Power Stage

\- \[x] Three-phase inverter topology defined

\- \[x] Power MOSFET selected: Infineon BSC066N06NS

\- \[x] Gate driver selected: TI DRV8323S

\- \[x] Six MOSFETs placed as three half bridges

\- \[x] VBUS rail added

\- \[x] Phase A/B/C switching nodes defined

\- \[x] Gate resistor footprints added

\- \[x] GHA/GHB/GHC and GLA/GLB/GLC nets defined

\- \[x] SHA/SHB/SHC connected to phase nodes

\- \[ ] DRV8323 support capacitors

\- \[ ] Current shunts

\- \[ ] DC-link capacitors

\- \[ ] Input protection

\- \[ ] Full power-stage schematic review

\- \[ ] PCB layout



\## Current Schematic



!\[Rev A Power Stage - Work in Progress](Exports/Power\_Stage\_Sch\_10-17-26.pdf)



Current Rev A schematic progress showing the DRV8323S gate driver and

three half bridges built from six BSC066N06NS 60 V N-channel MOSFETs.



The schematic is still a work in progress. Low-side current shunts,

driver support circuitry, DC-link capacitance, and input protection

have not yet been finalized.

