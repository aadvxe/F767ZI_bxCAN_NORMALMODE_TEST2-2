# F767ZI bxCAN Normal Mode Test (Backup Copy 2)

> [!NOTE]
> This folder is a preserved duplicate/backup archive of [`F767ZI_bxCAN_NORMALMODE_TEST2`](file:///c:/Users/Rangga/Documents/Old%20Project%20Archive/F767ZI_bxCAN_NORMALMODE_TEST2).

---

## 🎯 Overview

An embedded STM32CubeIDE project for the **NUCLEO-F767ZI** evaluation board demonstrating CAN bus normal mode (`CAN_MODE_NORMAL`) communication with periodic frame transmission and interrupt-driven reception.

- **MCU:** STM32F767ZIT6 (ARM Cortex-M7 @ 216 MHz)
- **Board:** NUCLEO-F767ZI
- **CAN Controller:** bxCAN (`CAN1`)
- **Mode:** `CAN_MODE_NORMAL`

---

## ⚙️ CAN Settings Summary

- **Instance:** `CAN1`
- **Bit Timing:** Prescaler = 4, BS1 = 15TQ, BS2 = 2TQ, SJW = 1TQ
- **Filter Bank:** Filter 0, ID Mask (accepts all frames into FIFO0)
- **Transmit Message:** StdId `0x321`, DLC = 2 (`[0x03, 0xAD]`) every 10 ms
- **Receive Callback:** Checks for StdId `0x321` and toggles Green LED `LD1` (`PB0`)

For detailed wiring diagrams, file layouts, and build instructions, please refer to the primary project:
👉 [F767ZI_bxCAN_NORMALMODE_TEST2 README](file:///c:/Users/Rangga/Documents/Old%20Project%20Archive/F767ZI_bxCAN_NORMALMODE_TEST2/README.md)
