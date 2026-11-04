# Geehy Cross-Series Resources | 极海跨系列资源索引

This page is a navigation index inside [Geehy-MCU-SDK](https://github.com/GeehySemi/Geehy-MCU-SDK). It links to existing GeehySemi repositories; it does not create a new source or package repository.

本页是 [Geehy-MCU-SDK](https://github.com/GeehySemi/Geehy-MCU-SDK) 中的跨系列资源导航索引，链接到 GeehySemi 组织下已有仓库，不在这里重复存放源码或软件包。

## How to use | 使用说明

Check each linked repository for its README, supported device list, version, board requirements, and release notes. A resource is marked for a Geehy MCU only when its repository documents that support.

使用资源前，请查看对应仓库的 README、支持器件列表、版本、开发板要求和更新说明。只有仓库明确列出支持范围时，本页才标注对应的极海型号。

## Operating systems and middleware | 操作系统与中间件

| Resource | Purpose | Documented Geehy support |
| --- | --- | --- |
| [mbed-os](https://github.com/GeehySemi/mbed-os) | Mbed OS source | The repository README does not list a Geehy MCU support matrix. Check target ports and examples before treating a model as supported. |
| [LittleFS](https://github.com/GeehySemi/LittleFS) | Filesystem for internal or SPI Flash | APM32F103 and APM32F107 are listed as supported. |
| [CherryUSB](https://github.com/GeehySemi/CherryUSB) | USB host/device stack | Check the repository's Geehy port and examples for the exact supported MCU. |
| [tinyusb](https://github.com/GeehySemi/tinyusb) | USB stack source | The repository currently has no README, so its Geehy ports and supported MCUs are not documented here. |

### RTOS support status | RTOS 支持现状

The public resources include an Mbed OS source repository, but its README does not identify supported Geehy MCU models or a Geehy port matrix. This index therefore does not claim model-specific RTOS support or point to a dedicated Geehy RTOS repository.

目前公开资源中有 Mbed OS 源码仓库，但其 README 未列出已支持的极海 MCU 型号或移植矩阵。因此本索引暂不宣称具体型号已获得 RTOS 支持，也不指向一个专门的极海 RTOS 仓库。

If Geehy later maintains shared RTOS port code for multiple MCU families, that code can live in one component repository with family-specific port directories, while this index records supported models and versions. If an integration is maintained only with one MCU SDK, keep it with that SDK and link it here.

如果后续需要共同维护面向多个 MCU 系列的 RTOS 移植代码，可以放在一个中间件仓库中，并按系列设置端口目录；本索引再列明支持型号和版本。如果移植只服务于某个 MCU SDK，则放在对应 SDK 仓库并从本页链接即可。

## Display and GUI | 显示与图形界面

| Resource | Purpose | Documented Geehy support |
| --- | --- | --- |
| [LVGL port for APM32F427](https://github.com/GeehySemi/lv_port_apm32f427) | LVGL v9.4.0 display demo | APM32F427VGT6 with an SPI-connected ILI9341 240 × 320 display. |

## Board, firmware, and reference resources | 开发板、固件与参考资料

| Resource | Contents | Notes |
| --- | --- | --- |
| [APM32F4XX Resources](https://github.com/GeehySemi/APM32F4XX) | APM32F4 reference documents and SDRAM materials | Some documents are drafts or historical versions; verify against current product documentation. |
| [DAPLink Hardware Firmware](https://github.com/GeehySemi/mbed-os-DAPLINK-Hardware) | Prebuilt DAPLink firmware | Files identify APM32F103xB and APM32F407IG targets. Confirm the exact board and firmware role before flashing. |
| [GW3323 Development Resources](https://github.com/GeehySemi/GW3323) | Datasheet, SDK/environment guides, schematics, RV32 toolchain, downloader, and driver | Includes historical SDK packages; check the files and version notes in the repository. |

## Development tools and device support | 开发工具与器件支持包

| Resource | Contents | Notes |
| --- | --- | --- |
| [IAR Device Support Packages](https://github.com/GeehySemi/IAR-Package) | IAR add-ons for APM32E103, APM32F00x, APM32F0xx, APM32F1xx, APM32F4xx, and APM32S103 | Match the add-on to the exact MCU series and IAR version. |
| [OpenOCD Package](https://github.com/GeehySemi/Openocd) | Packaged OpenOCD v0.12.0-rc2 for 32-bit Windows/MinGW | This repository contains a binary package, not the full OpenOCD source. |
| [xPack Windows Build Tools](https://github.com/GeehySemi/xpack) | Windows build tools 4.3.0-1 archive | An archived tool package; check whether a project requires this version. |
| [J-Link Windows v7.70a](https://github.com/GeehySemi/JLink_Windows_V770a_x86_64) | 64-bit Windows J-Link archive | Check SEGGER licensing and current compatibility before use. |

## Examples and MCU-family resources | 示例与 MCU 系列资源

Peripheral examples and device-specific integrations are maintained with their MCU SDKs. Start from the [MCU SDK index](https://github.com/GeehySemi/Geehy-MCU-SDK) and choose the target series.

外设示例和器件专用移植由对应 MCU SDK 仓库维护。请先从 [MCU SDK 索引](https://github.com/GeehySemi/Geehy-MCU-SDK) 选择目标系列，再查看该系列的示例和说明。
