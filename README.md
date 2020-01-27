# BX31_DemoOctaveSystem
Bluetooth scanner which feeds it's data to the Legato DataHub - to be used with SierraWireless Octaveand the BX31 Bluetooth IoT card https://github.com/tseiman/IoT_BX31_Card

It is meant as an demo to show the difference of a pure Legato imoplementation - which can be found here: https://github.com/tseiman/SWILegatoBTScanner_BX31_AVS

There is clear advantage in required code ammount:
- Code required in pure Linux Implementation: **2500LOC** (logical lines of code - no coment whitespaces etc counted)
- Code required in Legato: **1200LOC**
- Code required in Octave: **406LOC** of C code and **98LOC** in JavaScript

To reach the same functionality.
