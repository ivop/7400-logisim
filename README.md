# 7400-logisim
Logisim library of 7400-series ICs

All circuits are intended for good 'ol Logisim 2.7.1.
Should also work with Logisim-ITA.
Don't know about Evolution which seems to constantly break older circuits, which is the reason I keep using the original version.
Despite some of its UI related bugs, it is a fixed target.
New circuits are added on a need-to-have basis (or when I'm bored).
Have fun!

| Part | Description | Symbol | Circuit | Notes |
| --- | --- | --- | --- | --- |
| 74LS01, 74LS03, 74LS09, 74LS26, 74LS38, 74LS39 | quad 2-input NAND gate, open-collector | ![](png/nand2_oc.png) | [NAND2_OC.circ](circ/NAND_OC.circ) | |
| 74LS05, 74LS06 , 74LS16 | hex inverter, open-collector | ![](png/inv_oc.png) | [INV_OC.circ](circ/INV_OC.circ) | |
| 74LS07, 74LS17, 74LS35 | hex buffer, open-collector | ![](png/buf_oc.png) | [BUF_OC.circ](circ/BUF_OC.circ) | |
| 74LS12, 74LS15 | triple 3-input NAND gate, open-collector | ![](png/nand3_oc.png) | [NAND3_OC.circ](circ/NAND3_OC.circ) | |
| 74LS22 | dual 4-input NAND gate, open-collector | ![](png/nand4_oc.png) | [NAND4_OC.circ](circ/NAND4_OC.circ) | |
| 74LS33 | quad 2-input NOR gate, open-collector | ![](png/nor2_oc.png) | [NOR2_OC.circ](circ/NOR2_OC.circ) | |
| 74LS41 | BCD to decimal decoder / Nixie tube driver, open-collector | ![](png/74LS41.png) | [74LS41.circ](circ/74LS41.circ) | |
| 74LS42 | BCD to decimal decoder | ![](png/74LS42.png) | [74LS42.circ](circ/74LS42.circ) | |
| 74LS46, 74LS47 | BCD to 7-segment decoder/driver, open-collector | ![](png/74LS46.png) | [74LS46.circ](circ/74LS46.circ) | |
| 74LS48 | BCD to 7-segment decoder/driver, open-collector, internal pull-up | ![](png/74LS48.png) | [74LS48.circ](circ/74LS48.circ) | |
| 74LS49 | BCD to 7-segment decoder/driver, open-collector | ![](png/74LS49.png) | [74LS49.circ](circ/74LS49.circ) | |
| 74LS51 | 3-3-input AND-OR-Invert gate and 2-2-input AND-OR-Invert gate | ![](png/74LS51.png) | [74LS51.circ](circ/74LS51.circ) | |
| 74LS74 | dual D positive edge triggered flip-flop | ![](png/74LS74.png) | [74LS74.circ](circ/74LS74.circ) | |
| 74LS75 | 4-bit bistable latch, complementary outputs | ![](png/74LS75.png) | [74LS75.circ](circ/74LS75.circ) | |
| 74LS77 | 4-bit bistable latch | ![](png/74LS77.png) | [74LS77.circ](circ/74LS77.circ) | |
| 74LS82 | 2-bit binary full adder | ![](png/74LS82.png) | [74LS82.circ](circ/74LS82.circ) | |
| 74LS83 | 4-bit binary full adder | ![](png/74LS83.png) | [74LS83.circ](circ/74LS83.circ) | |
| 74LS90 | decade counter | ![](png/74LS90.png) | [74LS90.circ](circ/74LS90.circ) | |
| 74LS92 | divide-by-12 counter | ![](png/74LS92.png) | [74LS92.circ](circ/74LS92.circ) | |
| 74LS93 | 4-bit binary counter | ![](png/74LS93.png) | [74LS93.circ](circ/74LS93.circ) | |
| 74LS138 | 3-to-8 line decoder/demultiplexer, inverting outputs| ![](png/74LS138.png) | [74LS138.circ](circ/74LS138.circ) | |
| 74LS147 | 10-line to 4-line priority encoder | ![](png/74LS147.png) | [74LS147.circ](circ/74LS147.circ) | |
| 74LS155 | dual 2-to-4 line decoder/demultiplexer, inverting outputs | ![](png/74LS155.png) | [74LS155.circ](circ/74LS155.circ) | |
| 74LS157 | quad 2-line to 1-line data selector/multiplexer, non-inverting outputs | ![](png/74LS157.png) | [74LS157.circ](circ/74LS157.circ) | |
| 74LS163 | synchronous presettable 4-bit binary counter, synchronous clear | ![](png/74LS163.png) | [74LS163.circ](circ/74LS163.circ) | |
| 74LS164 | 8-bit serial-in parallel-out (SIPO) shift register, asynchronous clear | ![](png/74LS164.png) | [74LS164.circ](circ/74LS164.circ) | |
| 74LS165 | 8-bit parallel-in serial-out (PISO) shift register, parallel load, complementary outputs | ![](png/74LS165.png) | [74LS165.circ](circ/74LS165.circ) | |
| 74LS166 | parallel-load 8-bit shift register | ![](png/74LS166.png) | [74LS166.circ](circ/74LS166.circ) | |
| 74LS169 | synchronous presettable 4-bit up/down binary counter | ![](png/74LS169.png) | [74LS169.circ](circ/74LS169.circ) | |
| 74LS175 | quad D edge-triggered flip-flop, complementary outputs and asynchronous clear | ![](png/74LS175.png) | [74LS175.circ](circ/74LS175.circ) | |
| 74LS240 | octal buffer, inverting outputs, three-state | ![](png/74LS240.png) | [74LS240.circ](circ/74LS240.circ) | |
| 74LS241 | octal buffer, non-inverting outputs, three-state | ![](png/74LS241.png) | [74LS241.circ](circ/74LS241.circ) | |
| 74LS244 | octal buffer, non-inverting outputs, three-state | ![](png/74LS244.png) | [74LS244.circ](circ/74LS244.circ) | |
| 74LS390 | dual 4-bit decade counter, asynchronous clear | ![](png/74LS390.png) | [74LS390.circ](circ/74LS390.circ) | |
| 74LS393 | dual 4-bit binary counter, asynchronous clear | ![](png/74LS393.png) | [74LS393.circ](circ/74LS393.circ) | |
