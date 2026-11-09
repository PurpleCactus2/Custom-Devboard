# Custom-Devboard
An RP2040 devboard meant for a completely custom and streamlined electronics development experience!
<img width="737" height="815" alt="PCB Render1" src="https://github.com/user-attachments/assets/f36168d7-3fcd-43db-8ecc-567ed0dd381d" />


## Introduction
This is a completely custom devboard made with the wonderful guide by [@Kai Pereira](https://blueprint.hackclub.com/starter-projects/devboard)

It features:

- An RP2040 microcontroller
- All 30 GPIO pins of the RP2040 broken out, with plently power and debugging pins as well
- 2MB of flash storage

## PCB and Schematic

### Schematic
My schematic uses a mostly similar layout to the one suggested in the guide, however, I have also included a diode and VSYS pin so that you can connect an external battery/power source to power the board. In addition to this, I have also changed the external pin layout a little in a way that makes more sense to me, but you'll see what I mean.

Here are a couple of screenshots of the schematic:

The RP2040 with its decoupling capacitors:<br>
<img width="434" height="653" alt="Microcontroller" src="https://github.com/user-attachments/assets/094cf45e-4938-4fd7-91e9-d72f33571d17" /><br>

The USB-C port (you can also see the diode I added here):<br>
<img width="415" height="290" alt="USB-C" src="https://github.com/user-attachments/assets/9d67c6e0-8b65-4b37-835b-8c3d8f42e5c4" /><br>

The flash memory along with the BOOTSEL button:<br>
<img width="412" height="235" alt="Flash" src="https://github.com/user-attachments/assets/d0bc64e7-d0ca-439d-b6bd-b4d331de0a59" /><br>

The 12MHz crystal oscillator:<br>
<img width="416" height="142" alt="Crystal" src="https://github.com/user-attachments/assets/56ebbc69-7f20-4ff6-8498-ccff67ea35a5" /><br>

The IO pins with a slightly changed layout:<br>
<img width="418" height="362" alt="IO" src="https://github.com/user-attachments/assets/bf546991-7984-4e61-a370-7ec139c4bee0" /><br>

### PCB
This is my first time using SMD so my layout and routing are a little atrocious. But I have tried my best to keep everything as logical as possible.

Here are a couple screenshots of the PCB:

The RP2040 footprint with decoupling caps, crystal and flash:<br>
<img width="664" height="785" alt="MCU Screenshot" src="https://github.com/user-attachments/assets/15a61efb-2311-4718-88ef-79816f95b5e5" /><br>

The whole board:<br>
<img width="286" height="617" alt="Board Screenshot " src="https://github.com/user-attachments/assets/178eb7b3-b249-4028-9b58-e51f567a711e" /><br>

Final render:<br>
<img width="500" height="892" alt="PCB Render2" src="https://github.com/user-attachments/assets/43926981-30b9-4f70-bd5a-8218e31cd061" /><br>

## BOM
|  | Item | Qty | Supplier | Cost/item | Total Cost | link |
|---|---|---|---|---|---|---|
|  | RP2040 | 1 | LCSC | $1.10 | $1.10 | [LCSC](https://www.lcsc.com/product-detail/C2040.html) |
|  | MCP1700 | 1 | LCSC | $0.44 | $0.44 | [LCSC](https://www.lcsc.com/product-detail/C39051.html) |
|  | Crystal | 1 | LCSC | $0.46 | $0.46 | [LCSC](https://www.lcsc.com/product-detail/C9002.html) |
|  | Flash memory | 1 | LCSC | $1.92 | $1.92 | [LCSC](https://www.lcsc.com/product-detail/C2456208.html) |
|  | Button | 1 | LCSC | $0.51 | $0.51 | [LCSC](https://www.lcsc.com/product-detail/C720477.html) |
|  | USB-C Port | 1 | LCSC | $0.87 | $0.87 | [LCSC](https://www.lcsc.com/product-detail/C165948.html) |
|  | Passive Components | 1 | LCSC | $1.57 | $1.57 | [100nF](https://www.lcsc.com/product-detail/C1525.html) [1uF](https://www.lcsc.com/product-detail/C2803380.html) [10uF](https://www.lcsc.com/product-detail/C1691.html) [33pF](https://www.lcsc.com/product-detail/C107005.html) [Diode](https://www.lcsc.com/product-detail/C49231016.html) [5.1KΩ](https://www.lcsc.com/product-detail/C2906874.html) [27Ω](https://www.lcsc.com/product-detail/C2909343.html) [1KΩ](https://www.lcsc.com/product-detail/C2906899.html) [10KΩ](https://www.lcsc.com/product-detail/C2906861.html) |
|  | PCB | 1 | JLCPCB | $4.10 | $4.10 | [LCSC](https://cart.jlcpcb.com/quote?stencilLayer=2&stencilWiddth=100&stencilLength=100&stencilCounts=5&plateType=1&spm=Jlcpcb.Homepage.1010) |
|  | Estimated total shipping |  |  |  | $17.57 |  |
|  | Total |  |  |  | $28.54 |  |

*I am willing to cover any extra charges that might apply*

### Cart Screenshots

LCSC Order:<br>
<img width="1408" height="536" alt="JLCPCB" src="https://github.com/user-attachments/assets/31df39d4-ecd4-4733-9823-5733eb9a94e2" /><br>
<img width="1443" height="603" alt="LCSC1" src="https://github.com/user-attachments/assets/780488de-f5ee-42cd-8ff1-e304ed19f055" /><br>
<img width="1446" height="713" alt="LCSC2" src="https://github.com/user-attachments/assets/88faa1c1-d3af-4e28-863d-e8168a55c30d" /><br>
<img width="1413" height="726" alt="LCSC3" src="https://github.com/user-attachments/assets/04207569-468b-4950-ab6d-43eba2a1491a" /><br>
<img width="1438" height="724" alt="LCSC4" src="https://github.com/user-attachments/assets/8ee3da58-a75e-44e3-847d-108ea88edb3d" /><br>

JLCPCB Order:<br>
<img width="1408" height="536" alt="JLCPCB" src="https://github.com/user-attachments/assets/3fdba74c-1e34-4f7e-a3e6-1461df3d135e" />
















