# 7400-logisim
Logisim library of 7400-series ICs

All circuits are intended for good 'ol Logisim 2.7.1.
Should also work with Logisim-ITA.
Don't know about Evolution which seems to constantly break older circuits, which is the reason I keep using the original version.
Despite some of its UI related bugs, 2.7.1 is a fixed target.
New circuits are added on a need-to-have basis (or when I'm bored).
Have fun!

* [1-99](#1-99)
* [100-199](#100-199)
* [200-299](#200-299)
* [300-399](#300-399)
* [400-499](#400-499)

## 1-99

| Part | Description | Symbol | Circuit | Notes |
| --- | --- | --- | --- | --- |
| 74LS01, 74LS03, 74LS09, 74LS26, 74LS38, 74LS39 | quad 2-input NAND gate, open-collector | ![](png/nand2_oc.png) | [NAND2_OC.circ](circ/NAND2_OC.circ) | |
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
| 74LS67 | AND gated J-K master-slave flip-flop, asynchronous preset and clear | ![](png/74LS67.png) | [74LS67.circ](circ/74LS67.circ) | |
| 74L68 | dual J-K flip-flop, asynchronous clear | ![](png/74L68.png) | [74LS68.circ](circ/74L68.circ) | |
| 74LS68 | dual 4-bit decade counters | ![](png/74LS68.png) | [74LS68.circ](circ/74LS68.circ) | |
| 74LS69 | dual 4-bit binary counters | ![](png/74LS69.png) | [74LS69.circ](circ/74LS69.circ) | |
| 74LS74 | dual D positive edge triggered flip-flop | ![](png/74LS74.png) | [74LS74.circ](circ/74LS74.circ) | |
| 74LS75 | 4-bit bistable latch, complementary outputs | ![](png/74LS75.png) | [74LS75.circ](circ/74LS75.circ) | |
| 74LS77 | 4-bit bistable latch | ![](png/74LS77.png) | [74LS77.circ](circ/74LS77.circ) | |
| 74LS78 | dual negative edge triggered J-K flip-flop, preset, common clock and common clear | ![](png/74LS78.png) | [74LS78.circ](circ/74LS78.circ) | |
| 74LS82 | 2-bit binary full adder | ![](png/74LS82.png) | [74LS82.circ](circ/74LS82.circ) | |
| 74LS83 | 4-bit binary full adder | ![](png/74LS83.png) | [74LS83.circ](circ/74LS83.circ) | |
| 74LS85 | 4-bit magnitude comparator | ![](png/74LS85.png) | [74LS85.circ](circ/74LS85.circ) | |
| 74LS87 | 4-bit true/complement/zero/one element | ![](png/74LS87.png) | [74LS87.circ](circ/74LS87.circ) | |
| 74LS90 | decade counter | ![](png/74LS90.png) | [74LS90.circ](circ/74LS90.circ) | |
| 74LS91 | 8-bit shift register, serial in, serial out, gated input | ![](png/74LS91.png) | [74LS91.circ](circ/74LS91.circ) | |
| 74LS92 | divide-by-12 counter | ![](png/74LS92.png) | [74LS92.circ](circ/74LS92.circ) | |
| 74LS93 | 4-bit binary counter | ![](png/74LS93.png) | [74LS93.circ](circ/74LS93.circ) | |
| 74LS94 | 4-bit shift register, dual asynchronous presets | ![](png/74LS94.png) | [74LS94.circ](circ/74LS94.circ) | |
| 74LS95 | 4-bit shift register, parallel in, parallel out, serial input | ![](png/74LS95.png) | [74LS95.circ](circ/74LS95.circ) | |
| 74LS96 | 5-bit parallel-in/parallel-out shift register, asynchronous preset | ![](png/74LS96.png) | [74LS96.circ](circ/74LS96.circ) | |
| 74LS97 | synchronous 6-bit binary rate multiplier | ![](png/74LS97.png) | [74LS97.circ](circ/74LS97.circ) | |
| 74LS98 | 4-bit data selector/storage register | ![](png/74LS98.png) | [74LS98.circ](circ/74LS98.circ) | |
| 74LS99 | 4-bit bidirectional universal shift register | ![](png/74LS99.png) | [74LS99.circ](circ/74LS99.circ) | |

## 100-199
[back to top](#7400-logisim)

| Part | Description | Symbol | Circuit | Notes |
| --- | --- | --- | --- | --- |
| 74LS100 | dual 4-bit bistable latch | ![](png/74LS100.png) | [74LS100.circ](circ/74LS100.circ) | |
| 74LS101 | AND-OR-gated J-K negative-edge-triggered flip-flop, preset | ![](png/74LS101.png) | [74LS101.circ](circ/74LS101.circ) | |
| 74LS102 | AND-gated J-K negative-edge-triggered flip-flop, preset and clear | ![](png/74LS102.png) | [74LS102.circ](circ/74LS102.circ) | |
| 74LS103 | dual J-K negative-edge-triggered flip-flop, clear | ![](png/74LS103.png) | [74LS103.circ](circ/74LS103.circ) | |
| 74LS104 | J-K master-slave flip-flop | ![](png/74LS104.png) | [74LS104.circ](circ/74LS104.circ) | |
| 74LS105 | J-K master-slave flip-flop, J2 and K2 inverted | ![](png/74LS105.png) | [74LS105.circ](circ/74LS105.circ) | |
| 74LS106 | dual J-K negative-edge-triggered flip-flop, preset and clear | ![](png/74LS106.png) | [74LS106.circ](circ/74LS106.circ) | |
| 74LS107 | dual J-K flip-flop, clear | ![](png/74LS107.png) | [74LS107.circ](circ/74LS107.circ) | |
| 74LS108 | dual J-K negative-edge-triggered flip-flop, preset, common clear and common clock | ![](png/74LS108.png) | [74LS108.circ](circ/74LS108.circ) | |
| 74LS109 | dual J-NotK positive-edge-triggered flip-flop, clear and preset | ![](png/74LS109.png) | [74LS109.circ](circ/74LS109.circ) | |
| 74LS110 | AND-gated J-K master-slave flip-flop, data lockout | ![](png/74LS110.png) | [74LS110.circ](circ/74LS110.circ) | |
| 74LS111 | dual J-K master-slave flip-flop, data lockout, reset, set | ![](png/74LS111.png) | [74LS111.circ](circ/74LS111.circ) | |
| 74LS112 | dual J-K negative-edge-triggered flip-flop, clear and preset | ![](png/74LS112.png) | [74LS112.circ](circ/74LS112.circ) | |
| 74LS113 | dual J-K negative-edge-triggered flip-flop, preset | ![](png/74LS113.png) | [74LS113.circ](circ/74LS113.circ) | |
| 74LS114 | dual J-K negative-edge-triggered flip-flop, preset, common clock and clear | ![](png/74LS114.png) | [74LS114.circ](circ/74LS114.circ) | |
| 74LS115 | dual J-K master-slave flip-flop, data lockout, reset | ![](png/74LS115.png) | [74LS115.circ](circ/74LS115.circ) | |
| 74L116 | dual 4-bit latch, clear | ![](png/74L116.png) | [74L116.circ](circ/74L116.circ) | |
| 74LS118 | hex set/reset latch, common reset | ![](png/74LS118.png) | [74LS118.circ](circ/74LS118.circ) | |
| 74LS120 | dual pulse synchronizer/drivers  | ![](png/74LS120.png) | [74LS120.circ](circ/74LS120.circ) | |
| 74LS125 | quad bus buffer, negative enable, three-state | ![](png/74LS125.png) | [74LS125.circ](circ/74LS125.circ) | |
| 74LS126 | quad bus buffer, positive enable, three-state | ![](png/74LS126.png) | [74LS126.circ](circ/74LS126.circ) | |
| 74LS131 | 3-to-8 line decoder/demultiplexer, address register, inverting outputs | ![](png/74LS131.png) | [74LS131.circ](circ/74LS131.circ) | |
| 74LS137 | 3-to-8 line decoder/demultiplexer, address latch, inverting outputs | ![](png/74LS137.png) | [74LS137.circ](circ/74LS137.circ) | |
| 74LS138 | 3-to-8 line decoder/demultiplexer, inverting outputs| ![](png/74LS138.png) | [74LS138.circ](circ/74LS138.circ) | |
| 74LS139 | dual 2-to-4 line decoder/demultiplexer, inverting outputs | ![](png/74LS139.png) | [74LS139.circ](circ/74LS139.circ) | |
| 74LS141 | BCD to decimal decoder/driver for cold-cathode indicator / Nixie tube | ![](png/74LS141.png)| [74LS141.circ](circ/74LS141.circ) | |
| 74LS142 | decade counter/latch/decoder/driver for Nixie tubes | ![](png/74LS142.png) | [74LS142.circ](circ/74LS142.circ) | |
| 74LS143 | decade counter/latch/decoder/7-segment driver | ![](png/74LS143.png) | [74LS143.circ](circ/74LS143.circ) | |
| 74LS144 | decade counter/latch/decoder/7-segment driver | ![](png/74LS144.png) | [74LS144.circ](circ/74LS144.circ) | |
| 74LS145 | BCD to decimal decoder/driver | ![](png/74LS145.png) | [74LS145.circ](circ/74LS145.circ) | |
| 74LS146 | 3-to-8 line decoder | ![](png/74LS146.png) | [74LS146.circ](circ/74LS146.circ) | |
| 74LS147 | 10-line to 4-line priority encoder | ![](png/74LS147.png) | [74LS147.circ](circ/74LS147.circ) | |
| 74LS148 | 8-line to 3-line priority encoder | ![](png/74LS148.png) | [74LS148.circ](circ/74LS148.circ) | |
| 74LS149 | 8-line to 8-line priority encoder | ![](png/74LS149.png) | [74LS149.circ](circ/74LS149.circ) | |
| 74LS150 | 16-line to 1-line data selector/multiplexer | ![](png/74LS150.png) | [74LS150.circ](circ/74LS150.circ) | |
| 74LS151 | 8-line to 1-line data selector/multiplexer | ![](png/74LS151.png) | [74LS151.circ](circ/74LS151.circ) | |
| 74LS152 | 8-line to 1-line data selector/multiplexer, inverting output | ![](png/74LS152.png) | [74LS152.circ](circ/74LS152.circ) | |
| 74LS153 | dual 4-line to 1-line data selector/multiplexer, non-inverting outputs | ![](png/74LS153.png) | [74LS153.circ](circ/74LS153.circ) | |
| 74LS154 | 4-to-16 line decoder/demultiplexer, inverting outputs | ![](png/74LS154.png) | [74LS154.circ](circ/74LS154.circ) | |
| 74LS155 | dual 2-to-4 line decoder/demultiplexer, inverting outputs | ![](png/74LS155.png) | [74LS155.circ](circ/74LS155.circ) | |
| 74LS156 | dual 2-to-4 line decoder/demultiplexer, inverting outputs, open-collector | ![](png/74LS156.png) | [74LS156.circ](circ/74LS156.circ) | |
| 74LS157 | quad 2-line to 1-line data selector/multiplexer, non-inverting outputs | ![](png/74LS157.png) | [74LS157.circ](circ/74LS157.circ) | |
| 74LS158 | quad 2-line to 1-line data selector/multiplexer, inverting outputs | ![](png/74LS158.png) | [74LS158.circ](circ/74LS158.circ) | |
| 74LS159 | 4-to-16 line decoder/demultiplexer, open-collector | ![](png/74LS159.png) | [74LS159.circ](circ/74LS159.circ) | |
| 74LS160 | synchronous presettable 4-bit decade counter, asynchronous clear | ![](png/74LS160.png) | [74LS160.circ](circ/74LS160.circ) | |
| 74LS161 | synchronous presettable 4-bit binary counter, asynchronous clear | ![](png/74LS161.png) | [74LS161.circ](circ/74LS161.circ) | |
| 74LS162 | synchronous presettable 4-bit decade counter, synchronous clear| ![](png/74LS162.png) | [74LS162.circ](circ/74LS162.circ) | |
| 74LS163 | synchronous presettable 4-bit binary counter, synchronous clear | ![](png/74LS163.png) | [74LS163.circ](circ/74LS163.circ) | |
| 74LS164 | 8-bit serial-in parallel-out (SIPO) shift register, asynchronous clear | ![](png/74LS164.png) | [74LS164.circ](circ/74LS164.circ) | |
| 74LS165 | 8-bit parallel-in serial-out (PISO) shift register, parallel load, complementary outputs | ![](png/74LS165.png) | [74LS165.circ](circ/74LS165.circ) | |
| 74LS166 | parallel-load 8-bit shift register | ![](png/74LS166.png) | [74LS166.circ](circ/74LS166.circ) | |
| 74LS167 | synchronous decade rate multiplier  | ![](png/74LS167.png) | [74LS167.circ](circ/74LS167.circ) | |
| 74LS168 | synchronous presettable 4-bit up/down decade counter | ![](png/74LS168.png) | [74LS168.circ](circ/74LS168.circ) | datasheet bug fixed |
| 74LS169 | synchronous presettable 4-bit up/down binary counter | ![](png/74LS169.png) | [74LS169.circ](circ/74LS169.circ) | |
| 74LS170 | 16-bit register file (4x4), open-collector | ![](png/74LS170.png) | [74LS170.circ](circ/74LS170.circ) | |
| 74LS171 | quad D flip-flops, clear | ![](png/74LS171.png) | [74LS171.circ](circ/74LS171.circ) | |
| 74LS172 | 16-bit multiple port register file (8x2) | ![](png/74LS172.png) | [74LS172.circ](circ/74LS172.circ) | |
| 74LS173 | quad D flip-flop, asynchronous clear | ![](png/74LS173.png) | [74LS173.circ](circ/74LS173.circ) | |
| 74LS174 | hex D flip-flop, common asynchronous clear | ![](png/74LS174.png) | [74LS174.circ](circ/74LS174.circ) | |
| 74LS175 | quad D edge-triggered flip-flop, complementary outputs and asynchronous clear | ![](png/74LS175.png) | [74LS175.circ](circ/74LS175.circ) | |
| 74LS176 | presettable decade (bi-quinary) counter/latch | ![](png/74LS176.png) | [74LS176.circ](circ/74LS176.circ) | |
| 74LS177 | presettable binary counter/latch | ![](png/74LS177.png) | [74LS177.circ](circ/74LS177.circ) | |
| 74LS180 | 9-bit odd/even parity bit generator and checker | ![](png/74LS180.png) | [74LS180.circ](circ/74LS180.circ) | |
| 74LS181 | 4-bit arithmetic logic unit and function generator | ![](png/74LS181.png) | [74LS181.circ](circ/74LS181.circ) | |
| 74LS182 | lookahead carry generator | ![](png/74LS182.png) | [74LS182.circ](circ/74LS182.circ) | |
| 74LS183 | dual carry-save full adder | ![](png/74LS183.png) | [74LS183.circ](circ/74LS183.circ) | |
| 74LS189 | 64-bit RAM (16x4), 4 data inputs, 4 inverted data outputs | ![](png/74LS189.png) | [74LS189.circ](circ/74LS189.circ) | |
| 74LS190 | synchronous presettable up/down 4-bit decade counter | ![](png/74LS190.png) | [74LS190.circ](circ/74LS190.circ) | |
| 74LS191 | synchronous presettable up/down 4-bit binary counter | ![](png/74LS191.png) | [74LS191.circ](circ/74LS191.circ) | |
| 74LS192 | synchronous presettable up/down 4-bit decade counter, clear | ![](png/74LS192.png) | [74LS192.circ](circ/74LS192.circ) | |
| 74LS193 | synchronous presettable up/down 4-bit binary counter, clear | ![](png/74LS193.png) | [74LS193.circ](circ/74LS193.circ) | |
| 74LS194 | 4-bit bidirectional universal shift register | ![](png/74LS194.png) | [74LS194.circ](circ/74LS194.circ) | |
| 74LS195 | 4-bit parallel-access shift register | ![](png/74LS195.png) | [74LS195.circ](circ/74LS195.circ) | |
| 74LS196 | presettable 4-bit decade counter/latch | ![](png/74LS196.png) | [74LS196.circ](circ/74LS196.circ) | |
| 74LS197 | presettable 4-bit binary counter/latch | ![](png/74LS197.png) | [74LS197.circ](circ/74LS197.circ) | |
| 74LS198 | 8-bit bidirectional universal shift register | ![](png/74LS198.png) | [74LS198.circ](circ/74LS198.circ) | |
| 74LS199 | 8-bit universal shift register, J-NotK serial inputs | ![](png/74LS199.png) | [74LS199.circ](circ/74LS199.circ) | |

## 200-299
[back to top](#7400-logisim)

| Part | Description | Symbol | Circuit | Notes |
| --- | --- | --- | --- | --- |
| 74LS200 | 256-bit RAM (256x1), inverted output, three-state | ![](png/74LS200.png) | [74LS200.circ](circ/74LS200.circ) | |
| 74LS201 | 256-bit RAM (256x1), inverted output, three-state | ![](png/74LS201.png) | [74LS201.circ](circ/74LS201.circ) | |
| 74LS202 | 256-bit RAM (256x1), non-inverted output, three-state | ![](png/74LS202.png) | [74LS202.circ](circ/74LS202.circ) | |
| 74LS206 | 256-bit RAM (256x1), open-collector | ![](png/74LS206.png) | [74LS206.circ](circ/74LS206.circ) | |
| 74LS208 | 1024-bit RAM (256x4), separate data in- and outputs, three-state | ![](png/74LS208.png) | [74LS208.circ](circ/74LS208.circ) | |
| 74LS209 | 1024-bit RAM (1024x1), three-state | ![](png/74LS209.png) | [74LS209.circ](circ/74LS209.circ) | |
| 74LS210 | octal buffer, inverting, three-state | ![](png/74LS210.png) | [74LS210.circ](circ/74LS210.circ) | |
| 74LS214 | 1024-bit RAM (1024x1), three-state | ![](png/74LS214.png) | [74LS214.circ](circ/74LS214.circ) | |
| 74LS215 | 1024-bit RAM (1024x1) , three-state | ![](png/74LS215.png) | [74LS215.circ](circ/74LS215.circ) | |
| 74LS216 | 256-bit RAM (64x4), common I/O, three-state | ![](png/74LS216.png) | [74LS216.circ](circ/74LS216.circ) | |
| 74LS217 | 256-bit RAM (64x4), three-state | ![](png/74LS217.png) | [74LS217.circ](circ/74LS217.circ) | |
| 74LS218 | 256-bit RAM (32x8), three-state | ![](png/74LS218.png) | [74LS218.circ](circ/74LS218.circ) | |
| 74LS219 | 64-bit RAM (16x4), non-inverting outputs, three-state | ![](png/74LS219.png) | [74LS219.circ](circ/74LS219.circ) | |
| 74LS226 | 4-bit parallel latched bus transceiver, three-state | ![](png/74LS226.png) | [74LS226.circ](circ/74LS226.circ) | |
| 74LS230 | dual 4-bit buffer/driver, one inverted, one non-inverted; negative enable | ![](png/74LS230.png) | [74LS230.circ](circ/74LS230.circ) | |
| 74LS231 | dual 4-bit buffer/driver, both inverted; one positive and one negative enable | ![](png/74LS231.png) | [74LS231.circ](circ/74LS231.circ) | |
| 74LS237 | 3-to-8 line decoder/demultiplexer, address latch, active high outputs | ![](png/74LS237.png) | [74LS237.circ](circ/74LS237.circ) | |
| 74LS238 | 3-to-8 line decoder/demultiplexer, active high outputs | ![](png/74LS238.png) | [74LS238.circ](circ/74LS238.circ) | |
| 74LS239 | dual 2-to-4 line decoder/demultiplexer, active high outputs | ![](png/74LS239.png) | [74LS239.circ](circ/74LS239.circ) | |
| 74LS240 | octal buffer, inverting outputs, three-state | ![](png/74LS240.png) | [74LS240.circ](circ/74LS240.circ) | |
| 74LS241 | octal buffer, non-inverting outputs, three-state | ![](png/74LS241.png) | [74LS241.circ](circ/74LS241.circ) | |
| 74LS242 | quad bus transceiver, inverting outputs, three-state | ![](png/74LS242.png) | [74LS242.circ](circ/74LS242.circ) | |
| 74LS243 | quad bus transceiver, non-inverting outputs, three-state | ![](png/74LS243.png) | [74LS243.circ](circ/74LS243.circ) | |
| 74LS244 | octal buffer, non-inverting outputs, three-state | ![](png/74LS244.png) | [74LS244.circ](circ/74LS244.circ) | |
| 74LS245 | octal bus transceiver, non-inverting outputs | ![](png/74LS245.png) | [74LS245.circ](circ/74LS245.circ) | |
| 74LS246 | BCD to 7-segment decoder/driver, 30V, active low, open-collector | ![](png/74LS246.png) | [74LS246.circ](circ/74LS246.circ) | |
| 74LS247 | BCD to 7-segment decoder/driver, 15V, active low, open-collector | ![](png/74LS247.png) | [74LS247.circ](circ/74LS247.circ) | |
| 74LS248 | BCD to 7-segment decoder/driver, active high, open-collector, internal 2k pull-up | ![](png/74LS248.png) | [74LS248.circ](circ/74LS248.circ) | |
| 74LS249 | BCD to 7-segment decoder/driver, active high, open-collector | ![](png/74LS249.png) | [74LS249.circ](circ/74LS249.circ) | |
| 74LS250 | 1 of 16 data selector/multiplexer, three-state | ![](png/74LS250.png) | [74LS250.circ](circ/74LS250.circ) | |
| 74LS251 | 8-line to 1-line data selector/multiplexer, complementary outputs, three-state | ![](png/74LS251.png) | [74LS251.circ](circ/74LS251.circ) | |
| 74LS253 | dual 4-line to 1-line data selector/multiplexer, three-state | ![](png/74LS253.png) | [74LS253.circ](circ/74LS253.circ) | |
| 74LS255 | dual 2-to-4 line decoder/demultiplexer, inverting outputs, three-state | ![](png/74LS255.png) | [74LS255.circ](circ/74LS255.circ) | |
| 74LS256 | dual 4-bit addressable latch | ![](png/74LS256.png) | [74LS256.circ](circ/74LS256.circ) | |
| 74LS257 | quad 2-line to 1-line data selector/multiplexer, non-inverting outputs, three-state | ![](png/74LS257.png) | [74LS257.circ](circ/74LS257.circ) | |
| 74LS258 | quad 2-line to 1-line data selector/multiplexer, inverting outputs, three-state | ![](png/74LS258.png) | [74LS258.circ](circ/74LS258.circ) | |
| 74LS259 | 8-bit bit addressable input latch with clear | ![](png/74LS259.png) | [74LS259.circ](circ/74LS259.circ) | |
| 74LS261 | 2-bit by 4-bit parallel binary multiplier | ![](png/74LS261.png) | [74LS261.circ](circ/74LS261.circ) | |
| 74LS264 | look ahead carry generator | ![](png/74LS264.png) | [74LS264.circ](circ/74LS264.circ) | |
| 74LS265 | quad complementary output elements | ![](png/74LS265.png) | [74LS265.circ](circ/74LS265.circ) | |
| 74LS268 | hex D-type latches, common output control, common enable, three-state | ![](png/74LS268.png) | [74LS268.circ](circ/74LS268.circ) | |
| 74LS269 | 8-bit bidirectional binary counter | ![](png/74LS269.png) | [74LS269.circ](circ/74LS269.circ) | datasheet bugs fixed |
| 74LS273 | 8-bit register, asynchronous clear | ![](png/74LS273.png) | [74LS273.circ](circ/74LS273.circ) | |
| 74LS274 | 4-bit by 4-bit binary multiplier, three-state| ![](png/74LS274.png) | [74LS274.circ](circ/74LS274.circ) | |
| 74LS275 | 7-bit slice Wallace tree, three-state | ![](png/74LS275.png) | [74LS275.circ](circ/74LS275.circ) | |
| 74LS276 | quad J-NotK edge-triggered flip-flops, separate clocks, common preset and clear | ![](png/74LS276.png) | [74LS276.circ](circ/74LS276.circ) | |
| 74LS278 | 4-bit cascadeable priority registers, latched data inputs | ![](png/74LS278.png) | [74LS278.circ](circ/74LS278.circ) | |
| 74LS279 | quad set-reset latch | ![](png/74LS279.png) | [74LS279.circ](circ/74LS279.circ) | |
| 74LS280 | 9-bit odd/even parity bit generator/checker | ![](png/74LS280.png) | [74LS280.circ](circ/74LS280.circ) | |
| 74LS281 | 4-bit parallel binary accumulator | ![](png/74LS281.png) | [74LS281.circ](circ/74LS281.circ) | |
| 74LS282 | look-ahead carry generator, selectable carry inputs | ![](png/74LS282.png) | [74LS282.circ](circ/74LS282.circ) | |
| 74LS283 | 4-bit binary full adder, with carry in | ![](png/74LS283.png) | [74LS283.circ](circ/74LS283.circ) | |
| 74LS284 | 4-bit by 4-bit parallel binary multiplier (high order 4 bits of product) | ![](png/74LS284.png) | [74LS284.circ](circ/74LS284.circ) | |
| 74LS285 | 4-bit by 4-bit parallel binary multiplier (low order 4 bits of product) | ![](png/74LS285.png) | [74LS285.circ](circ/74LS285.circ) | |
| 74LS286 | 9-bit parity generator/checker, bus driver parity I/O port | ![](png/74LS286.png) | [74LS286.circ](circ/74LS286.circ) | |
| 74LS289 | 64-bit RAM (16x4), 4 data inputs, 4 inverted data outputs | ![](png/74LS289.png) | [74LS289.circ](circ/74LS289.circ) | |
| 74LS290 | decade counter (separate divide-by-2 and divide-by-5 sections) | ![](png/74LS290.png) | [74LS290.circ](circ/74LS290.circ) | |
| 74LS292 | programmable frequency divider/digital timer | ![](png/74LS292.png) | [74LS292.circ](circ/74LS292.circ) | |
| 74LS293 | 4-bit binary counter (separate divide-by-2 and divide-by-8 sections) | ![](png/74LS293.png) | [74LS293.circ](circ/74LS293.circ) | |
| 74LS294 | programmable frequency divider/digital timer | ![](png/74LS294.png) | [74LS294.circ](circ/74LS294.circ) | |
| 74LS295 | 4-bit bidirectional shift register, three-state | ![](png/74LS295.png) | [74LS295.circ](circ/74LS295.circ) | |
| 74LS298 | quad 2-input multiplexer, storage | ![](png/74LS298.png) | [74LS298.circ](circ/74LS298.circ) | |
| 74LS299 | 8-bit bidirectional universal shift/storage register, three-state | ![](png/74LS299.png) | [74LS299.circ](circ/74LS299.circ) | |


## 300-399
[back to top](#7400-logisim)

| Part | Description | Symbol | Circuit | Notes |
| --- | --- | --- | --- | --- |
| 74LS300 | 256-bit RAM (256x1), open-collector | ![](png/74LS300.png) | [74LS300.circ](circ/74LS300.circ) | |
| 74LS301 | 256-bit RAM (256x1), open-collector | ![](png/74LS301.png) | [74LS301.circ](circ/74LS301.circ) | |
| 74LS302 | 256-bit RAM (256x1), open-collector | ![](png/74LS302.png) | [74LS302.circ](circ/74LS302.circ) | |
| 74LS303 | octal divide-by-2 clock driver, 2 outputs inverted | ![](png/74LS303.png) | [74LS303.circ](circ/74LS303.circ) | |
| 74LS304 | octal divide-by-2 clock driver | ![](png/74LS304.png) | [74LS304.circ](circ/74LS304.circ) | |
| 74LS305 | octal divide-by-2 clock driver, 4 outputs inverted | ![](png/74LS305.png) | [74LS305.circ](circ/74LS305.circ) | |
| 74LS306 | 8-bit LV-TTL to GTL+ bus transceiver, three-state, open-collector | ![](png/74LS306.png) | [74LS306.circ](circ/74LS306.circ) | |
| 74LS309 | 1024-bit RAM (1024x1), open-collector | ![](png/74LS309.png) | [74LS309.circ](circ/74LS309.circ) | |
| 74LS310 | octal buffer, inverting, three-state | ![](png/74LS310.png) | [74LS310.circ](circ/74LS310.circ) | |
| 74LS314 | 1024-bit RAM (1024x1), open-collector | ![](png/74LS314.png) | [74LS314.circ](circ/74LS314.circ) | |
| 74LS315 | 1024-bit RAM (1024x1), open-collector | ![](png/74LS315.png) | [74LS315.circ](circ/74LS315.circ) | |
| 74LS316 | 256-bit RAM (64x4), common I/O, open-collector| ![](png/74LS316.png) | [74LS316.circ](circ/74LS316.circ) | |
| 74LS317 | 256-bit RAM (64x4), open-collector | ![](png/74LS317.png) | [74LS317.circ](circ/74LS317.circ) | |
| 74LS318 | 256-bit RAM (32x8), open-collector | ![](png/74LS318.png) | [74LS318.circ](circ/74LS318.circ) | |
| 74LS319 | 64-bit RAM (16x4), open-collector | ![](png/74LS319.png) | [74LS319.circ](circ/74LS319.circ) | |
| 74LS322 | 8-bit shift register, sign extend, three-state | ![](png/74LS322.png) | [74LS322.circ](circ/74LS322.circ) | |
| 74LS323 | 8-bit bidirectional universal shift/storage register, synchronous clear, three-state | ![](png/74LS323.png) | [74LS323.circ](circ/74LS323.circ) | |
| 74LS337 | clock driver, three-state | ![](png/74LS337.png) | [74LS337.circ](circ/74LS337.circ) | |
| 74LS340 | octal buffer, inverting outputs, three-state| ![](png/74LS340.png) | [74LS340.circ](circ/74LS340.circ) | |
| 74LS341 | octal buffer, non-inverting outputs, three-state | ![](png/74LS341.png) | [74LS341.circ](circ/74LS341.circ) | |
| 74LS344 | octal buffer, non-inverting outputs, three-state | ![](png/74LS344.png) | [74LS344.circ](circ/74LS344.circ) | |
| 74LS347 | BCD to 7-segment decoders/drivers, open-collector | ![](png/74LS347.png) | [74LS347.circ](circ/74LS347.circ) | |
| 74LS348 | 8 to 3-line priority encoder, three-state | ![](png/74LS348.png) | [74LS348.circ](circ/74LS348.circ) | |
| 74LS350 | 4-bit shifter, three-state | ![](png/74LS350.png) | [74LS350.circ](circ/74LS350.circ) | |
| 74LS351 | dual 8-line to 1-line data selectors/multiplexers, 4 common data inputs, three-state | ![](png/74LS351.png) | [74LS351.circ](circ/74LS351.circ) | |
| 74LS352 | dual 4-line to 1-line data selectors/multiplexers, inverting outputs | ![](png/74LS352.png) | [74LS352.circ](circ/74LS352.circ) | |
| 74LS353 | dual 4-line to 1-line data selectors/multiplexers, inverting outputs, three-state | ![](png/74LS353.png) | [74LS353.circ](circ/74LS353.circ) | |
| 74LS354 | 8-line to 1-line data selector/multiplexer, transparent registers, three-state | ![](png/74LS354.png) | [74LS354.circ](circ/74LS354.circ) | |
| 74LS355 | 8-line to 1-line data selector/multiplexer, transparent registers, open-collector | ![](png/74LS355.png) | [74LS355.circ](circ/74LS355.circ) | |
| 74LS356 | 8-line to 1-line data selector/multiplexer, edge-triggered registers, three-state | ![](png/74LS356.png) | [74LS356.circ](circ/74LS356.circ) | |
| 74LS357 | 8-line to 1-line data selector/multiplexer, edge-triggered registers, open-collector | ![](png/74LS357.png) | [74LS357.circ](circ/74LS357.circ) | |
| 74LS362 | four-phase clock generator/driver for Texas Instruments TMS9900 | ![](png/74LS362.png) | [74LS362.circ](circ/74LS362.circ) | |
| 74LS363 | octal transparent latch, three-state | ![](png/74LS363.png) | [74LS363.circ](circ/74LS363.circ) | |
| 74LS364 | octal edge-triggered D-type register, three-state | ![](png/74LS364.png) | [74LS364.circ](circ/74LS364.circ) | |
| 74LS365 | hex buffer, non-inverting outputs, three-state | ![](png/74LS365.png) | [74LS365.circ](circ/74LS365.circ) | |
| 74LS366 | hex buffer, inverting outputs, three-state | ![](png/74LS366.png) | [74LS366.circ](circ/74LS366.circ) | |
| 74LS367 | hex buffer, non-inverting outputs, three-state | ![](png/74LS367.png) | [74LS367.circ](circ/74LS367.circ) | |
| 74LS368 | hex buffer, inverting outputs three-state | ![](png/74LS368.png) | [74LS368.circ](circ/74LS368.circ) | |
| 74LS373 | octal transparent latch, three-state | ![](png/74LS373.png) | [74LS373.circ](circ/74LS373.circ) | |
| 74LS374 | octal register, three-state | ![](png/74LS374.png) | [74LS374.circ](circ/74LS374.circ) | |
| 74LS375 | quad bistable latch | ![](png/74LS375.png) | [74LS375.circ](circ/74LS375.circ) | |
| 74LS376 | quad J-NotK flip-flop, common clock and common clear | ![](png/74LS376.png) | [74LS376.circ](circ/74LS376.circ) | |
| 74LS377 | 8-bit register, clock enable | ![](png/74LS377.png) | [74LS377.circ](circ/74LS377.circ) | |
| 74LS378 | 6-bit register, clock enable | ![](png/74LS378.png) | [74LS378.circ](circ/74LS378.circ) | |
| 74LS379 | 4-bit register, clock enable and complementary outputs | ![](png/74LS379.png) | [74LS379.circ](circ/74LS379.circ) | |
| 74LS380 | 8-bit multifunction register, three-state | ![](png/74LS380.png) | [74LS380.circ](circ/74LS380.circ) | |
| 74LS381 | 4-bit arithmetic logic unit/function generator, generate and propagate outputs | ![](png/74LS381.png) | [74LS381.circ](circ/74LS381.circ) | |
| 74LS382 | 4-bit arithmetic logic unit/function generator, ripple carry and overflow outputs | ![](png/74LS382.png) | [74LS382.circ](circ/74LS382.circ) | |
| 74LS383 | 8-bit register, open-collector | ![](png/74LS383.png) | [74LS383.circ](circ/74LS383.circ) | |
| 74LS385 | quad serial adder/subtractor | ![](png/74LS385.png) | [74LS385.circ](circ/74LS385.circ) | |
| 74LS390 | dual 4-bit decade counter, asynchronous clear | ![](png/74LS390.png) | [74LS390.circ](circ/74LS390.circ) | |
| 74LS393 | dual 4-bit binary counter, asynchronous clear | ![](png/74LS393.png) | [74LS393.circ](circ/74LS393.circ) | |
| 74LS395 | 4-bit cascadable shift register, three-state | ![](png/74LS395.png) | [74LS395.circ](circ/74LS395.circ) | |
| 74LS396 | octal storage register, parallel access | ![](png/74LS396.png) | [74LS396.circ](circ/74LS396.circ) | |
| 74LS398 | quad 2-input multiplexers, storage, and complementary outputs | ![](png/74LS398.png) | [74LS398.circ](circ/74LS398.circ) | |
| 74LS399 | quad 2-input multiplexers, storage | ![](png/74LS399.png) | [74LS399.circ](circ/74LS399.circ) | |


## 400-499
[back to top](#7400-logisim)

| Part | Description | Symbol | Circuit | Notes |
| --- | --- | --- | --- | --- |
| 74LS405 | 3-to-8 line decoder, inverted outputs | ![](png/74LS405.png) | [74LS405.circ](circ/74LS405.circ) | |
| 74LS408 | 8-bit parity tree | ![](png/74LS408.png) | [74LS408.circ](circ/74LS408.circ) | |
| 74LS412 | multi-mode buffered 8-bit latch, three-state | ![](png/74LS412.png) | [74LS412.circ](circ/74LS412.circ) | |
| 74LS416 | modulo 10 counter, preload and clear inputs | ![](png/74LS416.png) | [74LS416.circ](circ/74LS416.circ) | |
| 74LS417 | modulo 2 and modulo 5 counters, common preload and clear inputs | ![](png/74LS417.png) | [74LS417.circ](circ/74LS417.circ) | |
| 74LS418 | modulo 16 counter, preload and clear inputs | ![](png/74LS418.png) | [74LS418.circ](circ/74LS418.circ) | |
| 74LS419 | dual modulo 4 counters, common preload and clear inputs | ![](png/74LS419.png) | [74LS419.circ](circ/74LS419.circ) | |
| 74LS425 | quad bus buffers, active low enables, three-state | ![](png/74LS425.png) | [74LS425.circ](circ/74LS425.circ) | |
| 74LS426 | quad bus buffers, active high enables, three-state | ![](png/74LS426.png) | [74LS426.circ](circ/74LS426.circ) | |
| 74LS432 | 8-bit multi-mode buffered latch, three-state | ![](png/74LS432.png) | [74LS432.circ](circ/74LS432.circ) | |
| 74LS436 | line driver/memory driver circuits - MOS memory interface, damping output resistor | ![](png/74LS436.png) | [74LS436.circ](circ/74LS436.circ) | |
| 74LS437 | line driver/memory driver circuits - MOS memory interface | ![](png/74LS437.png) | [74LS437.circ](circ/74LS437.circ) | |
| 74LS440 | quad tridirectional bus transceiver, non-inverting outputs, open-collector | ![](png/74LS440.png) | [74LS440.circ](circ/74LS440.circ) | |
| 74LS441 | quad tridirectional bus transceiver, inverting outputs, open-collector | ![](png/74LS441.png) | [74LS441.circ](circ/74LS441.circ) | |
| 74LS442 | quad tridirectional bus transceiver, non-inverting outputs, three-state | ![](png/74LS442.png) | [74LS442.circ](circ/74LS442.circ) | |
| 74LS443 | quad tridirectional bus transceiver, inverting outputs, three-state | ![](png/74LS443.png) | [74LS443.circ](circ/74LS443.circ) | |
| 74LS444 | quad tridirectional bus transceiver, inverting and non-inverting outputs, three-state | ![](png/74LS444.png) | [74LS444.circ](circ/74LS444.circ) | |
| 74LS445 | | ![](png/74LS445.png) | [74LS445.circ](circ/74LS445.circ) | |
| 74LS446 | | ![](png/74LS446.png) | [74LS446.circ](circ/74LS446.circ) | |
| 74LS447 | | ![](png/74LS447.png) | [74LS447.circ](circ/74LS447.circ) | |
| 74LS448 | quad tridirectional bus transceiver, inverting and non-inverting outputs, open-collector | ![](png/74LS448.png) | [74LS448.circ](circ/74LS448.circ) | |
| 74LS449 | | ![](png/74LS449.png) | [74LS449.circ](circ/74LS449.circ) | |
| 74LS450 | | ![](png/74LS450.png) | [74LS450.circ](circ/74LS450.circ) | |
| 74LS451 | | ![](png/74LS451.png) | [74LS451.circ](circ/74LS451.circ) | |
| 74LS453 | | ![](png/74LS453.png) | [74LS453.circ](circ/74LS453.circ) | |
| 74F455 | | ![](png/74F455.png) | [74F455.circ](circ/74F455.circ) | |
| 74F456 | | ![](png/74F456.png) | [74F456.circ](circ/74F456.circ) | |
