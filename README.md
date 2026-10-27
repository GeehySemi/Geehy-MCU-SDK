![Geehy Semiconductor](https://user-images.githubusercontent.com/110007518/224920727-7dd0e2db-2925-4535-8e1f-d754c35dc238.jpeg)

<p align="center">
  <a href="#english">English</a> ·
  <a href="#中文">中文</a> ·
  <a href="https://global.geehy.com/">Global Website</a> ·
  <a href="https://www.geehy.com/">中文官网</a> ·
  <a href="https://community.geehy.com/">Community</a>
</p>

# Geehy MCU SDK

<a id="english"></a>

## English

### Overview

This repository is the central index for official software development resources for Geehy Semiconductor microcontrollers.

It brings together the public SDK repositories for APM32 and G32 MCU families, along with evaluation-board resources, middleware ports, operating-system integrations, development tools, and selected reference projects.

This repository is an index and navigation hub only. Source code and release packages remain maintained in their corresponding repositories under the [GeehySemi organization](https://github.com/GeehySemi).

### Quick Start

1. Find your MCU series in the SDK index below.
2. Open the corresponding SDK repository.
3. Check the repository README, examples, package information, and release notes before starting development.
4. Use the related middleware, tools, and reference projects when needed.
5. For technical questions, open an Issue in the repository most closely related to your device or project.

## MCU SDK Repository Index

| Product Line | MCU Series | Official SDK | Evaluation / Reference Resources | Related Middleware / Ports |
| --- | --- | --- | --- | --- |
| APM32 | APM32F00x | [APM32F00x_SDK](https://github.com/GeehySemi/APM32F00x_SDK) | — | — |
| APM32 | APM32F0xx | [APM32F0xx_SDK](https://github.com/GeehySemi/APM32F0xx_SDK) | — | — |
| APM32 | APM32E030 | [APM32E030_SDK](https://github.com/GeehySemi/APM32E030_SDK) | - | - |
| APM32 | APM32E10x | [APM32E10x_SDK](https://github.com/GeehySemi/APM32E10x_SDK) | [APM32E10x_EVAL_SDK](https://github.com/GeehySemi/APM32E10x_EVAL_SDK) | — |
| APM32 | APM32F10x | [APM32F10x_SDK](https://github.com/GeehySemi/APM32F10x_SDK) | — | [LittleFS](https://github.com/GeehySemi/LittleFS) |
| APM32 | APM32F4xx | [APM32F4xx_SDK](https://github.com/GeehySemi/APM32F4xx_SDK) | [APM32F4XX Resources](https://github.com/GeehySemi/APM32F4XX) | [LVGL port for APM32F427](https://github.com/GeehySemi/lv_port_apm32f427) |
| APM32 | APM32F465 | [APM32F465_SDK](https://github.com/GeehySemi/APM32F465_SDK) | - | - |
| APM32 | APM32F402、APM32F403 | [APM32F402_403_SDK](https://github.com/GeehySemi/APM32F402_403_SDK) | - | - |
| APM32 | APM32F445、APM32F446 | [APM32F445_446_SDK](https://github.com/GeehySemi/APM32F445_446_SDK) | - | - |
| G32 | G32R5xx | [G32R5xx_SDK](https://github.com/GeehySemi/G32R5xx_SDK) | — | — |
| G32 | G32R430 | [G32R430_DDL_SDK](https://github.com/GeehySemi/G32R430_DDL_SDK) | — | — |


> The table reflects the SDK repositories currently published under GeehySemi. Additional MCU families and software resources will be added as they become available.

## Ecosystem and Middleware

| Project | MCU / Platform | Description |
| --- | --- | --- |
| [LittleFS](https://github.com/GeehySemi/LittleFS) | APM32F103 / APM32F107 | LittleFS port supporting internal Flash and external SPI Flash storage backends |
| [LVGL port for APM32F427](https://github.com/GeehySemi/lv_port_apm32f427) | APM32F427 | LVGL demonstration project for APM32F427-based GUI development |
| [Mbed OS](https://github.com/GeehySemi/mbed-os) | APM32 | Mbed OS repository containing APM32-related support |

## Development Tools

| Resource | Description |
| --- | --- |
| [OpenOCD](https://github.com/GeehySemi/Openocd) | Debugging and programming resources for APM32 devices |
| [IAR Package](https://github.com/GeehySemi/IAR-Package) | Device support packages for IAR Embedded Workbench |
| [APM32 Eclipse Development Kit for Windows](https://github.com/GeehySemi/APM32-Eclipse-development-Kit-for-Windows) | Eclipse-based development resources for APM32 on Windows |
| [DAPLink Hardware Resources](https://github.com/GeehySemi/mbed-os-DAPLINK-Hardware) | DAPLink-related firmware and hardware resources |
| [xPack](https://github.com/GeehySemi/xpack) | Package and development-environment related resources |

## Selected Reference Projects

### APM32F00x / APM32F0xx

- [APM32F003 Low-Power Example](https://github.com/GeehySemi/APM32F003_Low_Power_Example)
- [APM32F003 32-bit Timer Cascade Example](https://github.com/GeehySemi/APM32F003_Timer_Cascade_32bit_Example)
- [APM32F003 Flash EEPROM Emulation](https://github.com/GeehySemi/APM32F003_Flash_EEPROM_Emulation)
- [APM32F030 IAP Bootloader Example](https://github.com/GeehySemi/APM32F030_IAP_Bootloader_Example)
- [APM32F0xx I2C EEPROM Example](https://github.com/GeehySemi/APM32F0xx_I2C_EEPROM_Example)
- [APM32F051 ADC + Software I2C + OLED Example](https://github.com/GeehySemi/APM32F051_ADC_SoftwareI2C_OLED_Example)
- [APM32F072 USB Touch Keyboard](https://github.com/GeehySemi/APM32F072-USB-TSC-KEYBOARD)
- [APM32F072 USB Touch Mouse](https://github.com/GeehySemi/APM32F072-USB-TSC-MOUSE)

### APM32E103 / APM32F103

- [APM32E103 Flash EEPROM Emulation](https://github.com/GeehySemi/APM32E103_Flash_EEPROM_Emulation)
- [APM32E103 GPIO-Emulated I2C Example](https://github.com/GeehySemi/APM32E103_GPIO_Emulated_I2C_Example)
- [APM32E103 ILI9341 Example](https://github.com/GeehySemi/APM32E103_ILI9341_Example)
- [APM32E103 AHT10 Example](https://github.com/GeehySemi/APM32E103_AHT10_Example)
- [APM32E103 PCF8563 Example](https://github.com/GeehySemi/APM32E103-PCF8563)
- [APM32F103 CAN Porting Guide](https://github.com/GeehySemi/APM32F103_CAN_Porting_Guide)
- [APM32F103 GCC Makefile Example](https://github.com/GeehySemi/APM32F103_GCC_Makefile_Example)
- [APM32F103 USART Idle + DMA Example](https://github.com/GeehySemi/APM32F103_USART_Idle_DMA_Example)
- [APM32F103 USB CDC Virtual COM Port Example](https://github.com/GeehySemi/APM32F103_USB_CDC_VirtualCOMPort_Example)

### APM32F4xx

- [LVGL port for APM32F427](https://github.com/GeehySemi/lv_port_apm32f427)
- [APM32F407 ADC Multi-Channel Scan + DMA + Timer Example](https://github.com/GeehySemi/APM32F407_ADC_MultiChannel_Scan_DMA_TMR8_CC1_Example)
- [APM32F407 ADC DMA Temperature Example](https://github.com/GeehySemi/APM32F407_ADC_DMA_Temperature_Example)
- [APM32F407 ADC Temperature / VREF / VBAT Example](https://github.com/GeehySemi/APM32F407_ADC_Temperature_VREF_VBAT_Example)
- [APM32F407 DAC + ADC Voltage Example](https://github.com/GeehySemi/APM32F407_DAC_ADC_Voltage_Example)
- [APM32F4xx SPI2 DMA TX Example](https://github.com/GeehySemi/APM32F4xx_SPI2_DMA_TX_Example)
- [APM32F4xx USART DMA TX Example](https://github.com/GeehySemi/APM32F4xx_USART_DMA_TX_Example)
- [APM32F407 USB MSC Firmware Upgrade Bootloader Example](https://github.com/GeehySemi/APM32F407_USB_MSC_Firmware_Upgrade_Bootloader_Example)

## Support and Contribution

Before reporting a problem, check the README and existing Issues in the relevant repository. When opening an Issue, please include the MCU model, development board, SDK version, toolchain version, debugger/programmer, reproduction steps, and relevant logs or screenshots.

For additional product documentation, software packages, development tools, and technical support, visit:

- [Geehy Global Website](https://global.geehy.com/)
- [Geehy Chinese Website](https://www.geehy.com/)
- [Geehy Technical Community](https://community.geehy.com/)
- [All Public GeehySemi Repositories](https://github.com/orgs/GeehySemi/repositories?type=public)

---

<a id="中文"></a>

## 中文

### 概览

本仓库是极海半导体 MCU 软件开发资源的统一索引与导航入口。

这里集中整理 APM32 与 G32 MCU 系列已公开的官方 SDK 仓库，并汇总评估板资源、中间件移植、操作系统支持、开发工具及典型参考工程，方便开发者快速找到与目标器件对应的软件资源。

本仓库仅作为索引与导航入口，不重复存放各 SDK 的源代码和发布包。具体代码、版本与更新仍由 [GeehySemi](https://github.com/GeehySemi) 组织下的对应仓库独立维护。

### 快速开始

1. 在下方 SDK 索引中找到对应的 MCU 系列。
2. 进入对应的官方 SDK 仓库。
3. 开始开发前查看仓库 README、示例工程、软件包信息及版本说明。
4. 根据项目需求使用对应的中间件、开发工具或参考工程。
5. 遇到技术问题时，优先在与器件或项目最相关的仓库中提交 Issue。

## MCU SDK 仓库索引

| 产品线 | MCU 系列 | 官方 SDK | 评估板 / 参考资源 | 相关中间件 / 移植 |
| --- | --- | --- | --- | --- |
| APM32 | APM32F00x | [APM32F00x_SDK](https://github.com/GeehySemi/APM32F00x_SDK) | — | — |
| APM32 | APM32F0xx | [APM32F0xx_SDK](https://github.com/GeehySemi/APM32F0xx_SDK) | — | — |
| APM32 | APM32E030 | [APM32E030_SDK](https://github.com/GeehySemi/APM32E030_SDK) | - | - |
| APM32 | APM32E10x | [APM32E10x_SDK](https://github.com/GeehySemi/APM32E10x_SDK) | [APM32E10x_EVAL_SDK](https://github.com/GeehySemi/APM32E10x_EVAL_SDK) | — |
| APM32 | APM32F10x | [APM32F10x_SDK](https://github.com/GeehySemi/APM32F10x_SDK) | — | [LittleFS](https://github.com/GeehySemi/LittleFS) |
| APM32 | APM32F4xx | [APM32F4xx_SDK](https://github.com/GeehySemi/APM32F4xx_SDK) | [APM32F4XX 参考资源](https://github.com/GeehySemi/APM32F4XX) | [APM32F427 LVGL 移植](https://github.com/GeehySemi/lv_port_apm32f427) |
| APM32 | APM32F465 | [APM32F465_SDK](https://github.com/GeehySemi/APM32F465_SDK) | - | - |
| APM32 | APM32F402、APM32F403 | [APM32F402_403_SDK](https://github.com/GeehySemi/APM32F402_403_SDK) | - | - |
| APM32 | APM32F445、APM32F446 | [APM32F445_446_SDK](https://github.com/GeehySemi/APM32F445_446_SDK) | - | - |
| G32 | G32R5xx | [G32R5xx_SDK](https://github.com/GeehySemi/G32R5xx_SDK) | — | — |
| G32 | G32R430 | [G32R430_DDL_SDK](https://github.com/GeehySemi/G32R430_DDL_SDK) | — | — |

> 本表汇总当前已在 GeehySemi 公开发布的主要 MCU SDK。后续新增产品系列及软件生态资源时将持续补充。

## 开源生态与中间件

| 项目 | MCU / 平台 | 说明 |
| --- | --- | --- |
| [LittleFS](https://github.com/GeehySemi/LittleFS) | APM32F103 / APM32F107 | 支持片内 Flash 与外部 SPI Flash 的 LittleFS 移植项目 |
| [APM32F427 LVGL 移植](https://github.com/GeehySemi/lv_port_apm32f427) | APM32F427 | 面向 APM32F427 GUI 开发的 LVGL 示例工程 |
| [Mbed OS](https://github.com/GeehySemi/mbed-os) | APM32 | 包含 APM32 相关支持的 Mbed OS 仓库 |

## 开发工具

| 资源 | 说明 |
| --- | --- |
| [OpenOCD](https://github.com/GeehySemi/Openocd) | APM32 调试与程序下载相关资源 |
| [IAR Package](https://github.com/GeehySemi/IAR-Package) | IAR Embedded Workbench 器件支持包 |
| [APM32 Eclipse Development Kit for Windows](https://github.com/GeehySemi/APM32-Eclipse-development-Kit-for-Windows) | Windows 平台 APM32 Eclipse 开发资源 |
| [DAPLink Hardware Resources](https://github.com/GeehySemi/mbed-os-DAPLINK-Hardware) | DAPLink 相关固件与硬件资源 |
| [xPack](https://github.com/GeehySemi/xpack) | 软件包与开发环境相关资源 |

## 典型参考工程

### APM32F00x / APM32F0xx

- [APM32F003 低功耗示例](https://github.com/GeehySemi/APM32F003_Low_Power_Example)
- [APM32F003 32 位定时器级联示例](https://github.com/GeehySemi/APM32F003_Timer_Cascade_32bit_Example)
- [APM32F003 Flash 模拟 EEPROM](https://github.com/GeehySemi/APM32F003_Flash_EEPROM_Emulation)
- [APM32F030 IAP Bootloader 示例](https://github.com/GeehySemi/APM32F030_IAP_Bootloader_Example)
- [APM32F0xx I2C EEPROM 示例](https://github.com/GeehySemi/APM32F0xx_I2C_EEPROM_Example)
- [APM32F051 ADC + 软件 I2C + OLED 示例](https://github.com/GeehySemi/APM32F051_ADC_SoftwareI2C_OLED_Example)
- [APM32F072 USB 触摸键盘](https://github.com/GeehySemi/APM32F072-USB-TSC-KEYBOARD)
- [APM32F072 USB 触摸鼠标](https://github.com/GeehySemi/APM32F072-USB-TSC-MOUSE)

### APM32E103 / APM32F103

- [APM32E103 Flash 模拟 EEPROM](https://github.com/GeehySemi/APM32E103_Flash_EEPROM_Emulation)
- [APM32E103 GPIO 模拟 I2C 示例](https://github.com/GeehySemi/APM32E103_GPIO_Emulated_I2C_Example)
- [APM32E103 ILI9341 示例](https://github.com/GeehySemi/APM32E103_ILI9341_Example)
- [APM32E103 AHT10 示例](https://github.com/GeehySemi/APM32E103_AHT10_Example)
- [APM32E103 PCF8563 示例](https://github.com/GeehySemi/APM32E103-PCF8563)
- [APM32F103 CAN 移植指南](https://github.com/GeehySemi/APM32F103_CAN_Porting_Guide)
- [APM32F103 GCC Makefile 示例](https://github.com/GeehySemi/APM32F103_GCC_Makefile_Example)
- [APM32F103 USART 空闲中断 + DMA 示例](https://github.com/GeehySemi/APM32F103_USART_Idle_DMA_Example)
- [APM32F103 USB CDC 虚拟串口示例](https://github.com/GeehySemi/APM32F103_USB_CDC_VirtualCOMPort_Example)

### APM32F4xx

- [APM32F427 LVGL 移植](https://github.com/GeehySemi/lv_port_apm32f427)
- [APM32F407 ADC 多通道扫描 + DMA + 定时器触发](https://github.com/GeehySemi/APM32F407_ADC_MultiChannel_Scan_DMA_TMR8_CC1_Example)
- [APM32F407 ADC DMA 温度采集](https://github.com/GeehySemi/APM32F407_ADC_DMA_Temperature_Example)
- [APM32F407 ADC 温度 / VREF / VBAT 示例](https://github.com/GeehySemi/APM32F407_ADC_Temperature_VREF_VBAT_Example)
- [APM32F407 DAC + ADC 电压示例](https://github.com/GeehySemi/APM32F407_DAC_ADC_Voltage_Example)
- [APM32F4xx SPI2 DMA 发送示例](https://github.com/GeehySemi/APM32F4xx_SPI2_DMA_TX_Example)
- [APM32F4xx USART DMA 发送示例](https://github.com/GeehySemi/APM32F4xx_USART_DMA_TX_Example)
- [APM32F407 USB MSC 固件升级 Bootloader 示例](https://github.com/GeehySemi/APM32F407_USB_MSC_Firmware_Upgrade_Bootloader_Example)

## 技术支持与贡献

反馈问题前，建议先查看对应仓库的 README 和现有 Issues。提交 Issue 时，请尽量提供 MCU 型号、开发板、SDK 版本、工具链版本、调试器 / 下载器、问题复现步骤，以及相关日志或截图。

更多产品文档、软件包、开发工具及技术支持：

- [极海全球官网](https://global.geehy.com/)
- [极海中文官网](https://www.geehy.com/)
- [极海技术社区](https://community.geehy.com/)
- [GeehySemi 全部公开仓库](https://github.com/orgs/GeehySemi/repositories?type=public)
