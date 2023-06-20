![d944c41020e1aa6319c815a2241af5bd_245348954-9f3d5cb0-e9f8-48c8-b4e6-38c896d54da8](https://github.com/riosmpw/PicoRioCPU2641300/assets/100336131/056e5a0d-be9c-44c6-87a7-bae7d5c64946)


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

Table of Content

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

![](https://github.com/riosmpw/PicoRioCPU2641300/blob/main/docs/source/_static/picorio2641300.PNG?raw=true)

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

  ## About RIOS Lab

![86831b4376ec6a9615bb54533c442366_245438239-6aae13c6-50a5-40c3-9a4e-ed4c79d41c20](https://github.com/riosmpw/PicoRioCPU2641300/assets/100336131/5e085ae5-bd80-49a3-b2ad-feb41a9d79b3)


**Ecosystem Wants to be Free**

By David A. Patterson · Director of RIOS Lab

**RISC-V International Open Source Laboratory** (RIOS Lab) is a Shenzhen-based research facility focused on computer system architecture, supported by the Tsinghua-Berkeley Shenzhen Research Institute. As an Open Source and Nobel Prize Laboratory, RIOS Lab promotes open-source innovation and collaboration. Our philosophy is that the computer architecture ecosystem should be free for all to access and build upon.

In November 2019, RIOS Lab was officially unveiled. Under the leadership of 2017 A.M. Turing Award winner Prof. David A. Patterson and operational support from TBSI,  RIOS Lab will conduct cutting-edge research in RISC-V hardware and software technology. Patterson first proposed the Reduced Instruction Set Computer (RISC), an open and free instruction set architecture enabling a new era of processor innovation through open standard collaboration. Released in 2010, the latest Fifth Generation RISC has gained worldwide attention.

The name for the lab RIOS is also inspired by the Spanish word for “rivers.” It symbolizes the flow of information from many sources, coming together to create a whole that is greater than the sum of its parts.


