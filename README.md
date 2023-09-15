# Konfiguration einer Photovoltaik-Insel
Dieses Repository soll dazu dienen, alle bestehenden Probleme beim Betrieb der PV-Anlage in https://github.com/grasmax/s1/issues zu beschreiben und Lösungsmöglichkeiten aufzuzeigen.

Die Anlage besteht aus:
- 4 x Victron Solarmodul 360W,
- Victron Multiplus II 48/35,
- Victron MPPT 250/60,
- Victron Cerbo GX,
- Victron Lynx,
- 4x Pylontech US2000C 50Ah/2,5kWh,
- Controller:
    * Raspberry Pi CM4IO Board
    * CM4001032 Raspberry Pi Compute Module 4, 1GB-RAM, 32GB-eMMC, BCM2711, ARM Cortex-A72
    * raspberry pi os (32bit) v11
    * IO CREST JMB582 2 Port SATA III PCI-e 3.0 x1 Non-RAID Controller Karte Jmicro Chipsatz SI-PEX40148
    * 2TB WD20EFZX
- Gavazzi-Energiezähler EM540,
- diversen DC- und Datenkabeln und
- diversen Konfigurationsprogrammen.

Die Anlage befindet sich seit November 2022 tageweise im Testbetrieb.
Ein 24/7-Betrieb ist nicht möglich.

Eine mögliche Lösung für die in 
* https://github.com/grasmax/s1/issues/11
* https://github.com/grasmax/s1/issues/11
beschriebenen Probleme wird in 
* https://github.com/grasmax/AcOnOff/blob/main/doc/gh_schaltschema.pdf
vorgeschlagen.
