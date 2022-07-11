# PicoRioCPU2641300 Project

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![UPRJ_CI](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml) [![Caravel Build](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml)

| :exclamation: Important Note            |
|-----------------------------------------|

PicoRioCPU2641300 CPU Preliminary Specification

Revision History

| Revision | Date | Description | Comment |
|----------|------|-------------|---------|
| 0.1      |      |             |         |
|          |      |             |         |
|          |      |             |         |

#Table of Content

1. Overview
    1.1  PicoRioCPU2641300
    1.2 About PicoRio
2. Architecture
3. Features

1.1 PicoRioCPU2641300
---------------------

The PicoRioCPU2641300 device is a single core 64-bit general-purpose
microcontroller based on the RIOSLab RVH1 high performance RISC-V CPU core with
12 stage pipeline and out-of-order execution. The RISC-V processor core is
coupled with an Core Local Interrupter (CLINT), Timer and advanced debug
support.

The device operates from a 2.6 to 3.6 V power supply and available in –40 to +85
°C

temperature range. Several power saving modes provide the flexibility for
maximum

optimization between wake-up latency and power consumption, an especially
important

consideration in low power applications.

The above features make the PicoRioCPU2641300 devices suitable for a wide range
of

interconnection applications, especially in areas such as industrial control,
motor drives,

power monitor and alarm systems, consumer and handheld equipment, POS, vehicle
GPS,

LED display and so on.

1.2 About PicoRio
-----------------

>   PicoRio is an open source RISC -V hardware platform, used for RISC-V
>   software and hardware development and academic research.

>   PicoRio project includes three phases.

1.  the first phase (1.0) PicoRio -- Done -- : includes four 64bit RISC-V GC,
    support basic cache consistency. With a complete **Linux** (command line
    version) support, can launch Chromium OS kernel under the command line and
    V8 Javascript engine, used for software development.

2.  the second phase (2.0) PicoRio -- On Going -- : processor cores to ARM A75
    level performance, such as supporting more than **four cores** of high
    consistency protocol implementation. Cooperate with Imagination and
    integrated complete graphical pathways (**GPU** + Display Pipeline) have
    video encoding/decoding function, to run the graphically intensive
    applications, such as a web browser.

3.  the third phase (PicoRio 3.0) -- To Do -- : To further improve the
    performance of the CPU processor core performance ARM A78 and above level,
    support more than 64 core and the consistency of the mesh interconnection (
    **NoC**) , used in desktop client and server side.

>   PicoRio project in the process of development will also build the complete
>   processor design iterative process and a series of processor design,
>   assessment tools, including performance power consumption model, random
>   command generator, consistency verification tools, automatic design space
>   exploration tools etc.

2. Architecture
===============

![](media/e42686d83e63a6b39d293368280ea942.png)

3. Features
===========

-   Single 64 bits RISC-V core

    -   RIOSLab RVH1 High Performance Core

    -   12 Stage Pipeline

    -   4 Issue

    -   Out-of-Order Execution

    -   Support RV64IMAC RISC-V ISA

    -   32KB Private L1 D-Cache(VIPT)

    -   32KB Private L1 I-Cache(VIPT)

-   2KB SRAM for Boot ROM

-   Quad SPI Master with 2 Chip select, supports both SPI flash and SRAM
    interface

-   2 x UART

-   2 x Timer (32 Bit), 1ns resolution

-   WishBone compatible design

-   JTAG for DFT test
