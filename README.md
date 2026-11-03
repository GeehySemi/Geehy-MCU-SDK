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


## APM32 Industrial-Grade MCUs
The APM32 series comprises 32-bit MCUs based on Arm Cortex-M0+/M3/M4F cores. These MCUs deliver a blend of high performance, low power consumption, real-time capabilities, stability, security, and versatility, ensuring a rapid, straightforward, and flexible development experience. With diverse models catering to various applications, the APM32 lineup features a robust development ecosystem and finds extensive use in industrial control, automotive electronics, high-end consumer electronics, smart homes, new energy, and communication facilities.

| MCU Series | Official SDK | Evaluation / Reference Resources | Related Middleware / Ports |
| --- | --- | --- | --- |
| APM32F00x | [APM32F00x_SDK](https://github.com/GeehySemi/APM32F00x_SDK) | — | — |
 APM32F0xx | [APM32F0xx_SDK](https://github.com/GeehySemi/APM32F0xx_SDK) | — | — |
| APM32E030 | [APM32E030_SDK](https://github.com/GeehySemi/APM32E030_SDK) | - | - |
| APM32E10x | [APM32E10x_SDK](https://github.com/GeehySemi/APM32E10x_SDK) | [APM32E10x_EVAL_SDK](https://github.com/GeehySemi/APM32E10x_EVAL_SDK) | — |
| APM32F10x | [APM32F10x_SDK](https://github.com/GeehySemi/APM32F10x_SDK) | — | [LittleFS](https://github.com/GeehySemi/LittleFS) |
| APM32F4xx | [APM32F4xx_SDK](https://github.com/GeehySemi/APM32F4xx_SDK) | [APM32F4XX Resources](https://github.com/GeehySemi/APM32F4XX) | [LVGL port for APM32F427](https://github.com/GeehySemi/lv_port_apm32f427) |
| APM32F465 | [APM32F465_SDK](https://github.com/GeehySemi/APM32F465_SDK) | - | - |
| APM32F402、APM32F403 | [APM32F402_403_SDK](https://github.com/GeehySemi/APM32F402_403_SDK) | - | - |
| APM32F445、APM32F446 | [APM32F445_446_SDK](https://github.com/GeehySemi/APM32F445_446_SDK) | - | - |


## G32R50x Series
The G32R501 series delivers outstanding real-time control capabilities with its Arm® Cortex®-M52 core, based on the Arm v8.1-M architecture and enhanced by the Zidian math instruction extension. With support for Arm HeliumTM technology via the MVE (vector extension) solution, this series integrates advanced sensing, control peripherals, and a flexible interconnection system. Its wide operating temperature range (-40°C to 125°C), suitable for a wide range of fields such as new energy inverters, commercial power supplies, industrial automation, and new energy vehicles.

| MCU Series | Official SDK | Evaluation / Reference Resources | Related Middleware / Ports |
| --- | --- | --- | --- |
| G32R5xx | [G32R5xx_SDK](https://github.com/GeehySemi/G32R5xx_SDK) | — | — |


## G32R430 Series
This independently developed MCU is designed for encoder applications, delivering high-precision motion control and position feedback. It features a 128MHz Cortex-M52 core, proprietary ATAN electrical-angle computation instructions, a 16-bit high-precision ADC, rich analog peripherals, and high-speed communication interfaces to improve real-time servo feedback and encoder accuracy. It is ideal for industrial servo systems, embodied robots, and intelligent automation equipment.

| MCU Series | Official SDK | Evaluation / Reference Resources | Related Middleware / Ports |
| --- | --- | --- | --- |
| G32R430 | [G32R430_DDL_SDK](https://github.com/GeehySemi/G32R430_DDL_SDK) | — | — |


## Motor Control MCUs/SoCs
Geehy's high-integration, high-performance, and energy-efficient motor control MCUs/SoCs provide single-chip solutions that simplify system design and offer diverse product options. With built-in hardware accelerators and advanced motor control algorithms, they deliver efficient, smooth, and reliable operation for industrial automation, smart home appliances, power tools, and garden equipment.

| MCU Series | Official SDK | Evaluation / Reference Resources | Related Middleware / Ports |
| --- | --- | --- | --- |
| APM32F035 | [APM32F035_SDK](https://github.com/GeehySemi/APM32F035_SDK) | — | — |
| G32F031、G32M3122、G32M3114、G32M3115 | [G32F031_G32M31xx_DAL_SDK](https://github.com/GeehySemi/G32F031_G32M31xx_DAL_SDK) | — | — |
| G32M3101 | [G32M3101_DAL_SDK](https://github.com/GeehySemi/G32M3101_DAL_SDK) | — | — |
| APM32M3514 | [APM32M35xx_SDK](https://github.com/GeehySemi/APM32M35xx_SDK) | — | — |

> The table reflects the SDK repositories currently published under GeehySemi. Additional MCU families and software resources will be added as they become available.

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

## APM32工业级微控制器
APM32是基于Arm® Cortex®-M0+/M3/M4F内核的32位微控制器，集高性能、低功耗、实时性、稳定性、安全性、多功能、快速移植等特性于一体，提供快速、简易、灵活的开发体验，帮助用户节省开发成本，实现性能最优化。APM32产品阵容丰富，开发生态资源完善，已在工业控制、汽车电子、高端消费电子、智慧家居、新能源、以及通信设施等领域得到广泛使用。

 MCU 系列 | 官方 SDK | 评估板 / 参考资源 | 相关中间件 / 移植 |
| --- | --- | --- | --- |
| APM32F00x | [APM32F00x_SDK](https://github.com/GeehySemi/APM32F00x_SDK) | — | — |
 APM32F0xx | [APM32F0xx_SDK](https://github.com/GeehySemi/APM32F0xx_SDK) | — | — |
| APM32E030 | [APM32E030_SDK](https://github.com/GeehySemi/APM32E030_SDK) | - | - |
| APM32E10x | [APM32E10x_SDK](https://github.com/GeehySemi/APM32E10x_SDK) | [APM32E10x_EVAL_SDK](https://github.com/GeehySemi/APM32E10x_EVAL_SDK) | — |
| APM32F10x | [APM32F10x_SDK](https://github.com/GeehySemi/APM32F10x_SDK) | — | [LittleFS](https://github.com/GeehySemi/LittleFS) |
| APM32F4xx | [APM32F4xx_SDK](https://github.com/GeehySemi/APM32F4xx_SDK) | [APM32F4XX Resources](https://github.com/GeehySemi/APM32F4XX) | [LVGL port for APM32F427](https://github.com/GeehySemi/lv_port_apm32f427) |
| APM32F465 | [APM32F465_SDK](https://github.com/GeehySemi/APM32F465_SDK) | - | - |
| APM32F402、APM32F403 | [APM32F402_403_SDK](https://github.com/GeehySemi/APM32F402_403_SDK) | - | - |
| APM32F445、APM32F446 | [APM32F445_446_SDK](https://github.com/GeehySemi/APM32F445_446_SDK) | - | - |


## G32R50x 系列
G32R5系列实时控制MCU搭载Arm v8.1-M架构的Arm® Cortex®-M52内核及自研紫电数学指令扩展单元，支持基于矢量扩充方案（MVE）的Arm HeliumTM技术，集成高性能感知，控制外设和灵活的外设互联系统，支持-40°C~105°/125°C的宽环境工作温度，适用于新能源逆变器、商业电源、工业自动化、新能源汽车等广泛领域。

 MCU 系列 | 官方 SDK | 评估板 / 参考资源 | 相关中间件 / 移植 |
| --- | --- | --- | --- |
| G32R5xx | [G32R5xx_SDK](https://github.com/GeehySemi/G32R5xx_SDK) | — | — |


## G32R430 系列
G32R430作为极海首款低功耗、高性能、高精度编码器专用MCU，专为高精度运动控制与位置反馈场景设计。搭载Cortex-M52内核，最高主频128MHz，集成自研ATAN电角度计算扩展指令，配备16位高精度ADC等丰富模拟外设和高速通信接口，有助于增强伺服系统位置反馈实时性、提升编码器精度。适用于工业伺服系统、具身机器人、智能自动化设备等应用场景。

 MCU 系列 | 官方 SDK | 评估板 / 参考资源 | 相关中间件 / 移植 |
| --- | --- | --- | --- |
| G32R430 | [G32R430_DDL_SDK](https://github.com/GeehySemi/G32R430_DDL_SDK) | — | — |


## 电机控制MCU/SoC
极海高集成、高性能、高能效电机控制MCU/SoC，以单芯片方案赋能电机系统设计，为客户提供更丰富的产品选择。产品内置专用硬件加速器与先进电机控制算法，为电机高效、平稳与安全运行提供可靠支撑，可广泛应用于工业自动化、智能家电、电动工具及园林工具等领域。

 MCU 系列 | 官方 SDK | 评估板 / 参考资源 | 相关中间件 / 移植 |
| --- | --- | --- | --- |
| APM32F035 | [APM32F035_SDK](https://github.com/GeehySemi/APM32F035_SDK) | — | — |
| G32F031、G32M3122、G32M3114、G32M3115 | [G32F031_G32M31xx_DAL_SDK](https://github.com/GeehySemi/G32F031_G32M31xx_DAL_SDK) | — | — |
| G32M3101 | [G32M3101_DAL_SDK](https://github.com/GeehySemi/G32M3101_DAL_SDK) | — | — |
| APM32M3514 | [APM32M35xx_SDK](https://github.com/GeehySemi/APM32M35xx_SDK) | — | — |

> 本表汇总当前已在 GeehySemi 公开发布的主要 MCU SDK。后续新增产品系列及软件生态资源时将持续补充。

## 技术支持与贡献

反馈问题前，建议先查看对应仓库的 README 和现有 Issues。提交 Issue 时，请尽量提供 MCU 型号、开发板、SDK 版本、工具链版本、调试器 / 下载器、问题复现步骤，以及相关日志或截图。

更多产品文档、软件包、开发工具及技术支持：

- [极海全球官网](https://global.geehy.com/)
- [极海中文官网](https://www.geehy.com/)
- [极海技术社区](https://community.geehy.com/)
- [GeehySemi 全部公开仓库](https://github.com/orgs/GeehySemi/repositories?type=public)
