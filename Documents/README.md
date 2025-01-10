# B-L462E-CELL1 Discovery board

## Overview

The B-L462E-CELL1 Discovery kit is a turnkey development platform for cellular IoT devices. The Discovery kit contains a low-power Discovery main board powered by an LBAD0ZZ1SE module, a global coverage antenna, and a fan-out board. The LBAD0ZZ1SE module includes an STM32L462REY6TR microcontroller, an LBAD0XX1SC-DM ultra-small LTE Cat M/NB modem, and an ST4SIM-200M GSMA-certified embedded SIM with a prepaid cellular connectivity data plane. ST4SIM-200M can also be used as an embedded secure element (eSE) for application.

STMod+ and extended pins connectivity provide unlimited expansion capabilities with a large choice of specialized add-on boards. Moreover, the fan-out board supports add-on boards using mikroBUS™, ESP‑01, Grove I2C, Grove UART, and breadboard.

ST-LINK/V2-1 is integrated into the board, as the embedded in-circuit debugger and programmer for the STM32 MCU and USB Virtual COM port bridge.

## Getting started

- [User manual](https://www.st.com/resource/en/user_manual/um2743-discovery-kit-for-lte-cat-mnbiot-with-stm32l4-series-stmicroelectronics.pdf)

### ST-LINK driver installation and firmware upgrade (on Microsoft Windows)

1. Download the latest [ST-LINK driver](https://www.st.com/en/development-tools/stsw-link009.html).
2. Extract the archive and run `dpinst_amd64.exe`. Follow the displayed instructions.
3. Download the latest [ST-LINK firmware upgrade](https://www.st.com/en/development-tools/stsw-link007.html).
4. Extract the archive and run the `ST-LinkUpgrade.exe` program.
5. Connect the board to your PC using a USB cable and wait until the USB enumeration is completed.
6. In the **ST-Link Upgrade** program, press the **Device Connect** button.
7. When the ST-LINK driver is correctly installed, the current ST-LINK version is displayed.
8. Press the **Yes >>>>** button to start the firmware upgrade process.

## Technical reference

- [STM32L462RE microcontroller](https://www.st.com/en/microcontrollers-microprocessors/stm32l462re.html)
- [B-L462E-CELL1 board](https://www.st.com/en/evaluation-tools/b-l462e-cell1.html)
- [User manual](https://www.st.com/resource/en/user_manual/um2743-discovery-kit-for-lte-cat-mnbiot-with-stm32l4-series-stmicroelectronics.pdf)
- [Data brief](https://www.st.com/resource/en/data_brief/b-l462e-cell1.pdf)
- [Schematic](https://www.st.com/resource/en/schematic_pack/mb1508-l462re-c03_schematic.pdf)
