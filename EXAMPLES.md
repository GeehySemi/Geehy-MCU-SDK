# Independent Project Examples | 独立项目例程

This is a catalog of standalone Geehy example projects. Example source remains in each linked repository; this page provides two ways to find it: by MCU series and by function.

本页汇总极海组织下独立维护的项目例程。源代码继续保留在各自仓库，本页提供两种查找方式：按 MCU 系列查找，或按功能查找。

Board, toolchain, SDK, and example-version details below come from the linked repositories' READMEs. Missing details are marked “待补 / To be documented.” This index does not imply that every project has been independently built or tested on hardware.

下表中的开发板、工具链、SDK 和例程版本来自各仓库 README。信息不足时标为“待补 / To be documented”。本索引不代表所有项目都经过独立编译或硬件实测。

## Browse by MCU series | 按 MCU 系列查找

<a id="apm32f0xx"></a>
### APM32F0xx series | APM32F0xx 系列

| MCU | Example | Function | Board, toolchain, and status |
| --- | --- | --- | --- |
| APM32F003 | [APM32F003_Low_Power_Example](https://github.com/GeehySemi/APM32F003_Low_Power_Example) | Halt/WFI low-power entry and GPIO wake-up | README asks users to verify the board and toolchain; exact board and versions are **待补**. |
| APM32F003 | [APM32F003_Flash_EEPROM_Emulation](https://github.com/GeehySemi/APM32F003_Flash_EEPROM_Emulation) | Emulate EEPROM in internal Flash | MDK project is mentioned; board and toolchain versions are **待补**. |
| APM32F003 | [APM32F003_Timer_Cascade_32bit_Example](https://github.com/GeehySemi/APM32F003_Timer_Cascade_32bit_Example) | Cascade timers for 32-bit counting | README records APM32F003 MINI, MDK-ARM V5.36 / EWARM V9.20.2. Some project files are absent from the default branch; see the status note below. |
| APM32F030 | [APM32F030_IAP_Bootloader_Example](https://github.com/GeehySemi/APM32F030_IAP_Bootloader_Example) | IAP bootloader | The default branch currently contains only a README; no runnable source or protocol is present. |
| APM32F0xx | [APM32F0xx_Option_Bytes_Example](https://github.com/GeehySemi/APM32F0xx_Option_Bytes_Example) | Read/program option bytes and configure IWDG | MDK and IAR projects are mentioned; target board and exact tool versions are **待补**. Review the device manual before changing option bytes. |
| APM32F030 / F072 | [APM32F0xx_I2C_EEPROM_Example](https://github.com/GeehySemi/APM32F0xx_I2C_EEPROM_Example) | Access external I²C EEPROM | APM32F030 MINI or APM32F072 MINI; Keil MDK / IAR EWARM; example V1.0.1. |
| APM32F051 | [APM32F051_ADC_SoftwareI2C_OLED_Example](https://github.com/GeehySemi/APM32F051_ADC_SoftwareI2C_OLED_Example) | ADC sampling and software-I²C OLED | Distributed as a ZIP project package; board, OLED controller, and toolchain details are **待补**. |
| APM32F072 | [APM32F072-USB-TSC-MOUSE](https://github.com/GeehySemi/APM32F072-USB-TSC-MOUSE) | Map TSC touch input to a USB HID mouse | Verify the touch-electrode layout and PCB-specific calibration; exact board and toolchain are **待补**. |
| APM32F072 | [APM32F072-USB-TSC-KEYBOARD](https://github.com/GeehySemi/APM32F072-USB-TSC-KEYBOARD) | Map TSC touch input to USB HID keyboard keys | MDK project and board support files are included; exact board model and tool versions are **待补**. |

<a id="apm32e103"></a>
### APM32E103 series | APM32E103 系列

| Example | Function | Board and toolchain |
| --- | --- | --- |
| [APM32E103_GPIO_Emulated_I2C_Example](https://github.com/GeehySemi/APM32E103_GPIO_Emulated_I2C_Example) | GPIO-based software I²C master | APM32E103 MINI; Keil MDK-ARM; V1.0.0. |
| [APM32E103_Flash_EEPROM_Emulation](https://github.com/GeehySemi/APM32E103_Flash_EEPROM_Emulation) | Emulate EEPROM in internal Flash | APM32E103 MINI; Keil MDK-ARM; V1.0.0. |
| [APM32E103_AHT10_Example](https://github.com/GeehySemi/APM32E103_AHT10_Example) | Read temperature/humidity from AHT10 over I²C | APM32E103 MINI; Keil MDK-ARM; V1.0.1. |
| [APM32E103_ILI9341_Example](https://github.com/GeehySemi/APM32E103_ILI9341_Example) | Drive an ILI9341 TFT display | APM32E103 MINI; Keil MDK-ARM; V1.0.1. |
| [APM32E103-PCF8563](https://github.com/GeehySemi/APM32E103-PCF8563) | Read time from PCF8563 RTC over GPIO software I²C | APM32E103 MINI; Keil MDK-ARM; V1.0.1. |

<a id="apm32f103"></a>
### APM32F103 series | APM32F103 系列

| Example | Function | Board and toolchain |
| --- | --- | --- |
| [APM32F103_GCC_Makefile_Example](https://github.com/GeehySemi/APM32F103_GCC_Makefile_Example) | Build a SysTick time-base project with Make | APM32F103 MINI; GNU Arm Embedded Toolchain; GNU Make. |
| [APM32F103_USART_Idle_DMA_Example](https://github.com/GeehySemi/APM32F103_USART_Idle_DMA_Example) | USART idle-line receive and DMA transfer | APM32F103 MINI; APM32F10x SDK V1.8; MDK-ARM V5.36 / IAR EWARM V8.50.5. |
| [APM32F103_USB_CDC_VirtualCOMPort_Example](https://github.com/GeehySemi/APM32F103_USB_CDC_VirtualCOMPort_Example) | USB CDC virtual COM port | APM32F103 MINI; APM32F10x SDK V1.8; MDK-ARM V5.36; example V1.0.3. |
| [APM32F103-DHT11](https://github.com/GeehySemi/APM32F103-DHT11) | Read DHT11 temperature/humidity and report over USART1 | APM32F103 MINI; Keil MDK-ARM. |

<a id="apm32f4xx"></a>
### APM32F4xx series | APM32F4xx 系列

| MCU | Example | Function | Board, toolchain, and status |
| --- | --- | --- | --- |
| APM32F4xx | [APM32F4xx_USART_DMA_TX_Example](https://github.com/GeehySemi/APM32F4xx_USART_DMA_TX_Example) | USART transmit using DMA | Exact board and toolchain are **待补** in the README. |
| APM32F4xx | [APM32F4xx_SPI2_DMA_TX_Example](https://github.com/GeehySemi/APM32F4xx_SPI2_DMA_TX_Example) | SPI2 transmit using DMA | Exact board and toolchain are **待补** in the README. |
| APM32F407 | [APM32F407_ADC_DMA_Temperature_Example](https://github.com/GeehySemi/APM32F407_ADC_DMA_Temperature_Example) | Sample the internal temperature sensor with ADC and DMA | Distributed as a ZIP reference package; board and toolchain details are **待补**. |
| APM32F407 | [APM32F407_ADC_Temperature_VREF_VBAT_Example](https://github.com/GeehySemi/APM32F407_ADC_Temperature_VREF_VBAT_Example) | Sample internal temperature, VREF, and VBAT channels | Exact board and toolchain are **待补** in the README. |
| APM32F407 | [APM32F407_ADC_MultiChannel_Scan_DMA_TMR8_CC1_Example](https://github.com/GeehySemi/APM32F407_ADC_MultiChannel_Scan_DMA_TMR8_CC1_Example) | TMR8 CC1-triggered multi-channel ADC scan with DMA | APM32F407 MINI and an MDK project are listed. |
| APM32F407 | [APM32F407_DAC_ADC_Voltage_Example](https://github.com/GeehySemi/APM32F407_DAC_ADC_Voltage_Example) | Output voltage on DAC and sample it with ADC | APM32F407 MINI; MDK-ARM V5.36 / IAR EWARM V8.50.5. PA4 must connect to PA0. |
| APM32F407 | [APM32F407_USB_MSC_Firmware_Upgrade_Bootloader_Example](https://github.com/GeehySemi/APM32F407_USB_MSC_Firmware_Upgrade_Bootloader_Example) | Upgrade firmware from USB mass storage | Board, toolchain, Flash layout, and recovery details should be documented and checked before production use. |

<a id="other-series"></a>
### Other series | 其他系列

The current standalone-project search is concentrated on APM32. For G32 family resources, start from the [G32R5xx SDK](https://github.com/GeehySemi/G32R5xx_SDK); this catalog lists separate project repositories.

当前检索到的独立项目主要集中在 APM32。G32 系列资源请从 [G32R5xx SDK](https://github.com/GeehySemi/G32R5xx_SDK) 进入；本目录专门列出独立项目仓库。

## Browse by function | 按功能查找

<a id="communication"></a>
### Communication and interfaces | 通信与接口

- USART idle-line + DMA: [APM32F103_USART_Idle_DMA_Example](https://github.com/GeehySemi/APM32F103_USART_Idle_DMA_Example)
- USART DMA transmit: [APM32F4xx_USART_DMA_TX_Example](https://github.com/GeehySemi/APM32F4xx_USART_DMA_TX_Example)
- SPI2 DMA transmit: [APM32F4xx_SPI2_DMA_TX_Example](https://github.com/GeehySemi/APM32F4xx_SPI2_DMA_TX_Example)
- Software I²C: [APM32E103_GPIO_Emulated_I2C_Example](https://github.com/GeehySemi/APM32E103_GPIO_Emulated_I2C_Example), [APM32E103-PCF8563](https://github.com/GeehySemi/APM32E103-PCF8563)
- External I²C EEPROM: [APM32F0xx_I2C_EEPROM_Example](https://github.com/GeehySemi/APM32F0xx_I2C_EEPROM_Example)
- USB CDC: [APM32F103_USB_CDC_VirtualCOMPort_Example](https://github.com/GeehySemi/APM32F103_USB_CDC_VirtualCOMPort_Example)
- USB MSC firmware update: [APM32F407_USB_MSC_Firmware_Upgrade_Bootloader_Example](https://github.com/GeehySemi/APM32F407_USB_MSC_Firmware_Upgrade_Bootloader_Example)
- USB HID from touch input: [APM32F072-USB-TSC-MOUSE](https://github.com/GeehySemi/APM32F072-USB-TSC-MOUSE), [APM32F072-USB-TSC-KEYBOARD](https://github.com/GeehySemi/APM32F072-USB-TSC-KEYBOARD)
- CAN porting instructions: [APM32F103_CAN_Porting_Guide](https://github.com/GeehySemi/APM32F103_CAN_Porting_Guide) (guide, not a standalone demo project; the README contains inconsistent MCU-family wording, so confirm the target before use).

<a id="analog"></a>
### Analog and data acquisition | 模拟量与数据采集

- ADC with internal temperature sensor: [APM32F407_ADC_DMA_Temperature_Example](https://github.com/GeehySemi/APM32F407_ADC_DMA_Temperature_Example)
- Temperature, VREF, and VBAT: [APM32F407_ADC_Temperature_VREF_VBAT_Example](https://github.com/GeehySemi/APM32F407_ADC_Temperature_VREF_VBAT_Example)
- Multi-channel ADC triggered by a timer: [APM32F407_ADC_MultiChannel_Scan_DMA_TMR8_CC1_Example](https://github.com/GeehySemi/APM32F407_ADC_MultiChannel_Scan_DMA_TMR8_CC1_Example)
- DAC output sampled by ADC: [APM32F407_DAC_ADC_Voltage_Example](https://github.com/GeehySemi/APM32F407_DAC_ADC_Voltage_Example)
- ADC with OLED output: [APM32F051_ADC_SoftwareI2C_OLED_Example](https://github.com/GeehySemi/APM32F051_ADC_SoftwareI2C_OLED_Example)

<a id="storage-update"></a>
### Storage and firmware update | 存储与固件升级

- Flash EEPROM emulation: [APM32E103_Flash_EEPROM_Emulation](https://github.com/GeehySemi/APM32E103_Flash_EEPROM_Emulation), [APM32F003_Flash_EEPROM_Emulation](https://github.com/GeehySemi/APM32F003_Flash_EEPROM_Emulation)
- External EEPROM: [APM32F0xx_I2C_EEPROM_Example](https://github.com/GeehySemi/APM32F0xx_I2C_EEPROM_Example)
- IAP Bootloader entry: [APM32F030_IAP_Bootloader_Example](https://github.com/GeehySemi/APM32F030_IAP_Bootloader_Example) (README only; source is currently absent from the default branch).
- USB mass-storage firmware update: [APM32F407_USB_MSC_Firmware_Upgrade_Bootloader_Example](https://github.com/GeehySemi/APM32F407_USB_MSC_Firmware_Upgrade_Bootloader_Example)

<a id="sensors-display"></a>
### Sensors and displays | 传感器与显示

- Temperature/humidity: [APM32E103_AHT10_Example](https://github.com/GeehySemi/APM32E103_AHT10_Example), [APM32F103-DHT11](https://github.com/GeehySemi/APM32F103-DHT11)
- RTC: [APM32E103-PCF8563](https://github.com/GeehySemi/APM32E103-PCF8563)
- TFT display: [APM32E103_ILI9341_Example](https://github.com/GeehySemi/APM32E103_ILI9341_Example)
- OLED display: [APM32F051_ADC_SoftwareI2C_OLED_Example](https://github.com/GeehySemi/APM32F051_ADC_SoftwareI2C_OLED_Example)

<a id="power-timing-build"></a>
### Power, timing, and build setup | 低功耗、定时与构建环境

- Low-power Halt/WFI: [APM32F003_Low_Power_Example](https://github.com/GeehySemi/APM32F003_Low_Power_Example)
- Cascaded 32-bit timer: [APM32F003_Timer_Cascade_32bit_Example](https://github.com/GeehySemi/APM32F003_Timer_Cascade_32bit_Example) (default-branch files are incomplete; see above).
- GCC + Make: [APM32F103_GCC_Makefile_Example](https://github.com/GeehySemi/APM32F103_GCC_Makefile_Example)

## Related references | 相关参考资料

- [F103_FPU](https://github.com/GeehySemi/F103_FPU) is a reference archive, not a runnable APM32F103 hardware-FPU example. APM32F103 uses Cortex-M3, which does not have the Cortex-M4F-style hardware FPU.
- Option-byte configuration: [APM32F0xx_Option_Bytes_Example](https://github.com/GeehySemi/APM32F0xx_Option_Bytes_Example). Review the chip manual and preserve a recovery path before changing protection or boot settings.
