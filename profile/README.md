![Open-CMSIS-Pack](/profile/Open-CMSIS-Pack.png)

## About Open-CMSIS-Pack

The Open-CMSIS-Pack project offers a flexible and easy to use end to end development flow for embedded software - from project creation to software execution on real or virtual hardware.

## List of Repositories

### Specifications

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [Open-CMSIS-Pack-Spec](https://github.com/Open-CMSIS-Pack/Open-CMSIS-Pack-Spec) | A specification describing a delivery mechanism for software components, device parameters, and evaluation board support. It also defines the build tools for projects based on software packs. | Access the [pre-built specification directly](https://open-cmsis-pack.github.io/Open-CMSIS-Pack-Spec/main/html/index.html). |
| [Open-CMSIS-Pack-Taxonomy](https://github.com/Open-CMSIS-Pack/Open-CMSIS-Pack-Taxonomy) | Organizes Cclass and Cgroup definitions to access software [\<components\>](https://open-cmsis-pack.github.io/Open-CMSIS-Pack-Spec/main/html/pdsc_components_pg.html) and application programming interfaces [\<apis\>](https://open-cmsis-pack.github.io/Open-CMSIS-Pack-Spec/main/html/pdsc_apis_pg.html). | Refer to the [Readme.md](https://github.com/Open-CMSIS-Pack/Open-CMSIS-Pack-Taxonomy) file. |
| [Open-CMSIS-CDI-Spec](https://github.com/Open-CMSIS-Pack/Open-CMSIS-CDI-Spec) | A set of APIs to enable firmware updates, running IoT applications, and RTOSes on a broad range of devices. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/Open-CMSIS-CDI-Spec). |

### Ready-to-use Tools

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [CMSIS-Toolbox](https://github.com/Open-CMSIS-Pack/cmsis-toolbox) | A set of command-line tools for software packs. | The [documentation](https://github.com/Open-CMSIS-Pack/cmsis-toolbox/blob/main/docs/README.md) explains the download, installation, and configuration process. |
| [gen-pack](https://github.com/Open-CMSIS-Pack/gen-pack) | A library for scripts creating Open-CMSIS-Packs. | Refer to the [Readme.md](https://github.com/Open-CMSIS-Pack/gen-pack) file. |
| [gen-pack-action](https://github.com/Open-CMSIS-Pack/gen-pack-action) | A GitHub workflow action generating documentation and Open-CMSIS-Packs. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/gen-pack-action). |
| [vidx2pidx](https://github.com/Open-CMSIS-Pack/vidx2pidx) | A package index generator. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/vidx2pidx). |

### CMSIS-Toolbox Project Examples (*csolution projects*)

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [csolution-examples](https://github.com/Open-CMSIS-Pack/csolution-examples) | A collection of exemplary csolution-based projects. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/csolution-examples). |
| [vscode-get-started](https://github.com/Open-CMSIS-Pack/vscode-get-started) | Setup of VS Code environment along wiht an example project. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/vscode-get-started). |

### Tutorials for Creating Own Software Packs (Webinar Recordings in Readme.md)

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [Create-Scaleable-SW](https://github.com/Open-CMSIS-Pack/Create-Scalable-SW)   | Explains how to structure complex middleware stacks. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/Create-Scalable-SW). |
| [SW-Pack-HandsOn](https://github.com/Open-CMSIS-Pack/SW-Pack-HandsOn)   | Explains the steps to create a simple software pack. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/SW-Pack-HandsOn). |
| [DFP-Pack-HandsOn](https://github.com/Open-CMSIS-Pack/DFP-Pack-HandsOn) | Explains the steps to create a device family pack. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/DFP-Pack-HandsOn). |
| [BSP-Pack-HandsOn](https://github.com/Open-CMSIS-Pack/BSP-Pack-HandsOn) | Explains the steps to create a board support pack. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/BSP-Pack-HandsOn). |

### STM32 Packs with Generator Support

The following software packs support the [STM32CubeMX integration](https://github.com/Open-CMSIS-Pack/cmsis-toolbox/blob/main/docs/CubeMX.md) of the CMSIS-Toolbox. These packs are compatible with uVision v5.40 or higher. The packs support Arm Compiler 6, GCC, and IAR. LLVM is not supported due to STM32CubeMX restrictions. Many Board Support Packs contain software layers for [MDK-Middleware](https://www.keil.arm.com/packs/mdk-middleware-keil/overview/); refer to the pack link for more information.

| Repository | Pack Link   | Description  |
|------------|-------------|--------------|
| **DFP**    | [keil.arm.com/devices](https://www.keil.arm.com/devices/)  | Device Family Packs | 
| [STM32C0xx_DFP](https://github.com/Open-CMSIS-Pack/STM32C0xx_DFP) | [keil.arm.com/packs/stm32c0xx_dfp-keil](https://www.keil.arm.com/packs/stm32c0xx_dfp-keil) | STM32C0 Series |
| [STM32F4xx_DFP](https://github.com/Open-CMSIS-Pack/STM32F4xx_DFP) | [keil.arm.com/packs/stm32f4xx_dfp-keil](https://www.keil.arm.com/packs/stm32f4xx_dfp-keil) | STM32F4 Series |
| [STM32L4xx_DFP](https://github.com/Open-CMSIS-Pack/STM32L4xx_DFP) | [keil.arm.com/packs/stm32l4xx_dfp-keil](https://www.keil.arm.com/packs/stm32l4xx_dfp-keil) | STM32L4 Series |
| [STM32U5xx_DFP](https://github.com/Open-CMSIS-Pack/STM32U5xx_DFP) | [keil.arm.com/packs/stm32u5xx_dfp-keil](https://www.keil.arm.com/packs/stm32u5xx_dfp-keil) | STM32U5 Series |
| [STM32H7xx_DFP](https://github.com/Open-CMSIS-Pack/STM32H7xx_DFP) | [keil.arm.com/packs/stm32h7xx_dfp-keil](https://www.keil.arm.com/packs/stm32h7xx_dfp-keil) | STM32H7 Series |
| [STM32H7RSxx_DFP](https://github.com/Open-CMSIS-Pack/STM32H7RSxx_DFP) | [keil.arm.com/packs/stm32h7rsxx_dfp-keil](https://www.keil.arm.com/packs/stm32h7rsxx_dfp-keil) | STM32H7RS Series |
| [STM32F7xx_DFP](https://github.com/Open-CMSIS-Pack/STM32F7xx_DFP) | [keil.arm.com/packs/stm32f7xx_dfp-keil](https://www.keil.arm.com/packs/stm32f7xx_dfp-keil) | STM32F7 Series |
| **CMSIS-Driver**    | .  | Add CMSIS-Driver to DFP |
| [CMSIS-Driver_STM32](https://github.com/Open-CMSIS-Pack/CMSIS-Driver_STM32) | [keil.arm.com/packs/cmsis-driver_stm32-arm](https://www.keil.arm.com/packs/cmsis-driver_stm32-arm) | Shim layers: STM32HAL to CMSIS-Driver |
| **BSP**    | [keil.arm.com/boards](https://www.keil.arm.com/boards/)  | Board Support Packs |
| STM32F4 | . | . |
| [NUCLEO-F401RE_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-F401RE_BSP) | [keil.arm.com/packs/nucleo-f401re_bsp-keil](https://www.keil.arm.com/packs/nucleo-f401re_bsp-keil) | Nucleo Kit for STM32F401RE Series |
| [NUCLEO-F412ZG_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-F412ZG_BSP) | [keil.arm.com/packs/nucleo-f412zg_bsp-keil](https://www.keil.arm.com/packs/nucleo-f412zg_bsp-keil) | Nucleo Kit for STM32F412ZG Series |
| [NUCLEO-F429ZI_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-F429ZI_BSP) | [keil.arm.com/packs/nucleo-f429zi_bsp-keil](https://www.keil.arm.com/packs/nucleo-f429zi_bsp-keil) | Nucleo Kit for STM32F429ZI Series |
| [NUCLEO-F446RE_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-F446RE_BSP) | [keil.arm.com/packs/nucleo-f446re_bsp-keil](https://www.keil.arm.com/packs/nucleo-f446re_bsp-keil) | Nucleo Kit for STM32F446RE Series |
| [STM32F469I-DISCO_BSP](https://github.com/Open-CMSIS-Pack/STM32F469I-DISCO_BSP) | [keil.arm.com/packs/stm32f469i-disco_bsp-keil](https://www.keil.arm.com/packs/stm32f469i-disco_bsp-keil) | Discovery Kit for STM32F469I Series |
| STM32L4 | . | . |
| [B-L475E-IOT01A_BSP](https://github.com/Open-CMSIS-Pack/ST_B-L475E-IOT01A_BSP) | [keil.arm.com/packs/b-l475e-iot01a_bsp-keil-keil](https://www.keil.arm.com/packs/b-l475e-iot01a_bsp-keil) | IoT Kit with STM32L475VGTx |
| [NUCLEO-L476RG_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-L476RG_BSP) | [keil.arm.com/packs/nucleo-l476rg_bsp-keil](https://www.keil.arm.com/packs/nucleo-l476rg_bsp-keil) | Nucleo Kit for STM32L476RG Series |
| [STM32L496G-DISCO_BSP](https://github.com/Open-CMSIS-Pack/STM32L496G-DISCO_BSP) | [keil.arm.com/packs/stm32l496g-disco_bsp-keil](https://www.keil.arm.com/packs/stm32l496g-disco_bsp-keil) | Discovery Kit for STM32L469G Series |
| [STM32L4R9I-DISCO_BSP](https://github.com/Open-CMSIS-Pack/STM32L4R9I-DISCO_BSP) | [keil.arm.com/packs/stm32l4R9i-disco_bsp-keil](https://www.keil.arm.com/packs/stm32l4r9i-disco_bsp-keil) | Discovery Kit for STM32L4R9I Series |
| STM32U5 | . | . |
| [B-U585I-IOT02A_BSP](https://github.com/Open-CMSIS-Pack/ST_B-U585I-IOT02A_BSP) | [keil.arm.com/packs/b-u585i-iot02a_bsp-keil](https://www.keil.arm.com/packs/b-u585i-iot02a_bsp-keil) | IoT Kit with STM32U585AIIx |
| [STM32U575I-EV_BSP](https://github.com/Open-CMSIS-Pack/STM32U575I-EV_BSP) | [keil.arm.com/packs/stm32u575i-ev_bsp-keil](https://www.keil.arm.com/packs/stm32u575i-ev_bsp-keil) | Eval Kit for STM32U575I Series |
| STM32F7 | . | . |
| [NUCLEO-F746ZG_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-F746ZG_BSP) | [keil.arm.com/packs/nucleo-f746zg_bsp-keil](https://www.keil.arm.com/packs/nucleo-f746zg_bsp-keil) | Nucleo Kit for STM32F746ZG Series |
| [NUCLEO-F756ZG_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-F756ZG_BSP) | [keil.arm.com/packs/nucleo-f756zg_bsp-keil](https://www.keil.arm.com/packs/nucleo-f756zg_bsp-keil) | Nucleo Kit for STM32F756ZG Series |
| [STM32F746G-DISCO_BSP](https://github.com/Open-CMSIS-Pack/STM32F746G-DISCO_BSP) | [keil.arm.com/packs/stm32f746g-disco_bsp-keil](https://www.keil.arm.com/packs/stm32f746g-disco_bsp-keil) | Discovery Kit for STM32F746G Series |
| [STM32F769I-DISCO_BSP](https://github.com/Open-CMSIS-Pack/STM32F769I-DISCO_BSP) | [keil.arm.com/packs/stm32f769i-disco_bsp-keil](https://www.keil.arm.com/packs/stm32f769i-disco_bsp-keil) | Discovery Kit for STM32F769I Series |
| [STM32F769I-EVAL_BSP](https://github.com/Open-CMSIS-Pack/STM32F769I-EVAL_BSP) | [keil.arm.com/packs/stm32f769i-eval_bsp-keil](https://www.keil.arm.com/packs/stm32f769i-eval_bsp-keil) | Eval Kit for STM32F769I Series |
| STM32H7 | . | . |
| [NUCLEO-H743ZI2_BSP](https://github.com/Open-CMSIS-Pack/ST_NUCLEO-H743ZI2_BSP) | [keil.arm.com/packs/nucleo-h743zi2_bsp-keil](https://www.keil.arm.com/packs/nucleo-h743zi2_bsp-keil) | Nucleo Kit for STM32H743ZI Series |
| [STM32H735G-DK_BSP](https://github.com/Open-CMSIS-Pack/STM32H735G-DK_BSP) | [keil.arm.com/packs/stm32h735g-dk_bsp-keil](https://www.keil.arm.com/packs/stm32h735g-dk_bsp-keil) | Discover Kit for STM32H735G Series |
| [STM32H745I-DISCO_BSP](https://github.com/Open-CMSIS-Pack/STM32H745I-DISCO_BSP) | [keil.arm.com/packs/stm32h745i-disco_bsp-keil](https://www.keil.arm.com/packs/stm32h745i-disco_bsp-keil) | Discover Kit for STM32H745I Series |
| [STM32H7B3I-DK_BSP](https://github.com/Open-CMSIS-Pack/STM32H7B3I-DK_BSP) | [keil.arm.com/packs/stm32h7b3i-dk_bsp-keil](https://www.keil.arm.com/packs/stm32h7b3i-dk_bsp-keil) | Discover Kit for STM32H7B3I Series |
| [STM32H743I-EVAL_BSP](https://github.com/Open-CMSIS-Pack/STM32H743I-EVAL_BSP) | [keil.arm.com/packs/stm32h743i-eval_bsp-keil](https://www.keil.arm.com/packs/stm32h743i-eval_bsp-keil) | Eval Kit for STM32H743I Series |
| [STM32H7B3I-EVAL_BSP](https://github.com/Open-CMSIS-Pack/STM32H7B3I-EVAL_BSP) | [keil.arm.com/packs/stm32h7b3i-eval_bsp-keil](https://www.keil.arm.com/packs/stm32h7b3i-eval_bsp-keil) | Eval Kit for STM32H7B3I Series |

### More CMSIS Software Pack Examples

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [MDK-Middleware](https://github.com/ARM-software/MDK-Middleware) | Middelware for TCP/IP networking, File System, USB Device, USB Host with [reference applications](https://github.com/Open-CMSIS-Pack/cmsis-toolbox/blob/main/docs/ReferenceApplications.md#mdk-middleware-reference-applications).| [User's Manual](https://arm-software.github.io/MDK-Middleware/latest/General/index.html) |
| [Sensor SDK](https://github.com/Open-CMSIS-Pack/Sensor-SDK-Example) | Example of sensor middelware using [reference applications with Arduino shields](https://github.com/ReinhardKeil/cmsis-toolbox/blob/main/docs/ReferenceApplications.md#sensor-reference-applications). | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/Sensor-SDK-Example). |
| [lwIP](https://github.com/Open-CMSIS-Pack/lwIP) | lwIP Network Stack. | . |
| [NXP_iMXRT105x_MWP](https://github.com/Open-CMSIS-Pack/NXP_iMXRT105x_MWP) | NXP i.MXRT1051/1052 Device Series Middleware examples and CMSIS-Drivers Pack  | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/NXP_iMXRT105x_MWP). |
| [NXP_IMXRT1050-EVKB_BSP](https://github.com/Open-CMSIS-Pack/NXP_IMXRT1050-EVKB_BSP) | NXP IMXRT1050-EVKB Board Support Pack | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/NXP_IMXRT1050-EVKB_BSP). |

### Tools Source Code

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [devtools](https://github.com/Open-CMSIS-Pack/devtools) | Development repo of these command line tools: [packchk](https://github.com/Open-CMSIS-Pack/devtools/tree/main/tools/packchk), [packgen](https://github.com/Open-CMSIS-Pack/devtools/tree/main/tools/packgen), csloution ([projmgr](https://github.com/Open-CMSIS-Pack/devtools/tree/main/tools/projmgr)), and cbuild ([buildmgr](https://github.com/Open-CMSIS-Pack/devtools/tree/main/tools/buildmgr)). | Contains the specification of the [csolution project format](https://github.com/Open-CMSIS-Pack/devtools/blob/main/tools/projmgr/docs/Manual/Overview.md) and related files. |
| [cpackget](https://github.com/Open-CMSIS-Pack/cpackget) | Source code repository of the cpackget tool (part of the CMSIS-Toolbox) | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/cpackget). |



