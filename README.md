# I am going to be working on a new design of this flight controller.

-- Removing AT7456E based analog OSD and CVBS routing.
-- Targeting modern digital FPV systems.

Hoping to have the new hardware done next month if life chills out. 

on the real tho, losing your side link hurts wayyy more than your main girl.


# STM32F7_Based_FLight-controller
STM32F722RET6 Based Flight Controller with ICM-42688-P IMU, BMP388 Barometer, and much more!

Detailed Specification:
- MCU - STM32F722RET6
- Interial Measurement Unit (IMU) - ICM-42688-P
- Barometer - BMP388
- On-screen Display chip (OSD) - AT7456E
- SPI FLASH - W25Q256JVEIQ (256 Mbit QUAD SPI NOR FLASH)
- 9 V -- 2A Buck Converter - TPS54335ADRCR
- 5V -- 2A Buck Converter - TPS54335ADRCR
- 3.3 V -- 700 mA LDO - AZ1117-3.3

Connectors:
- 4 UARTs
- 3 SPIs
- 1 I2C

This flight controller is directly flashable and configurale via BetaFlight. Make sure to flash the FC with custom CLI file named "IRS_CLI". There is a official tutorial on youtube on how to flash a custom flight controller with a custom cli file.
