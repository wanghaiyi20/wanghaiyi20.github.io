---
layout: page
permalink: /projects/index.html
title: Projects

---

## High-Performance RISC-V Superscalar Processor Design

**Project Source:** National Major Scientific Instrument Development Project  
**Project Date:** 2025-06 ~ 2026-03

This project focuses on the design of a high-performance superscalar processor based on the RISC-V instruction set, targeting the demand for high-performance and low-power domestic processor architectures. The project explores superscalar instruction-level parallelism, event-structure-based parallelism analysis, bidirectional operand-fetch strategies, and large-scale out-of-order execution, aiming to improve instruction-level parallelism and overall processor performance under low-power constraints. The processor was taped out and verified using a 28nm process.

**Main Responsibilities:**

- **CPU core architecture design and RTL implementation**: Responsible for CPU core microarchitecture design and RTL development across key pipeline stages, including instruction fetch, decode, register renaming, issue, execution, and retirement. Completed RTL coding, interface integration, and functional verification for related modules.
- **Out-of-order issue module design**: Responsible for the design and implementation of out-of-order issue logic, including issue queues, instruction wake-up, issue arbitration, and operand selection. Supported parallel issue of multiple instructions and improved utilization of execution resources.
- **FPGA synthesis and simulation verification**: Completed logic synthesis, pre-simulation, and post-synthesis simulation of the issue module on an FPGA verification platform. Designed benchmarks for functional debugging and identified and fixed issues related to architecture design, RTL implementation, timing constraints, and module interfaces.
- **ASIC back-end verification and debugging**: Participated in logic synthesis, functional debugging, static timing analysis, dynamic timing verification, parasitic extraction, and physical layout verification in the ASIC flow. Supported multi-stage verification from RTL to layout implementation and gained practical experience across the complete chip development process from architecture to back-end verification.

<img src="{{ '/file/micor_arch.jpg' | relative_url }}">

---

## Low-Power RISC-V SoC Development and Application Demonstration

**Project Source:** Subproject of a Major Science and Technology Project of Gansu Province  
**Project Date:** 2023-10 ~ 2025-05

<img src="{{ '/file/版图.png' | relative_url }}" alt="profile" class="floatpic">

Targeting low-power, high-reliability, and radiation-tolerant application scenarios such as missile-borne computers and individual soldier equipment, this project develops a fully asynchronous processor and low-power SoC based on the 32-bit RISC-V IMC instruction set. The project adopts a “Sender–Relay–Receiver” asynchronous micropipeline structure and builds an interconnected system consisting of a processor core, SRAM, peripheral modules, and NoC nodes. The design was taped out and verified using a 40nm process.

**Main Responsibilities:**

- **Fully asynchronous RISC-V processor architecture design**: Responsible for the architecture design of a fully asynchronous RISC-V processor. Built an asynchronous micropipeline based on the “Sender–Relay–Receiver” structure, using the micropipeline to represent the direction and behavior of data movement inside the processor core, and implemented the RISC-V IMC instruction set.
- **Register renaming and issue module design**: Responsible for the design of the register renaming and issue modules. Completed RTL implementation, unit testing, and functional verification, including instruction dependency handling, physical register allocation, and instruction issue control.
- **Low-power SoC integration**: Participated in low-power SoC integration. Connected the processor core, SRAM, and peripheral modules through NoC nodes, and completed module interface definition, system interconnection, and integration debugging.
- **Verification flow and script organization**: Coordinated the development progress of module owners, organized DC synthesis scripts, VCS simulation scripts, and test benchmarks, and supported module-level verification and system-level issue localization.
- **Synthesis verification and netlist delivery**: Completed DC logic synthesis, Formality equivalence checking, and netlist delivery, and collaborated with the back-end team to complete tape-out verification based on a 40nm process.

---

## Development of an Asynchronous Circuit Logic Synthesis Tool for Emerging Semiconductor Processes

**Project Date:** 2025-11 ~ Present

This project focuses on developing a hierarchical logic synthesis tool for asynchronous circuit design automation targeting emerging semiconductor processes. The tool supports the transformation from high-level dataflow design to gate-level Verilog netlists. Based on the “Sender–Relay–Receiver” model, the project establishes a conversion flow among dataflow-level models, mesoscopic asynchronous models, and gate-level netlists. By introducing a virtual process library, the tool enables integration with commercial EDA tools and bridges high-level design methodology with emerging semiconductor process technologies.

**Main Contributions:**

- **Dataflow-level component library design**: Defined the functional semantics, port specifications, and graphical representation rules of asynchronous dataflow components. Implemented hardware descriptions and dataflow-level models for basic structural components, providing a reusable component foundation for high-level asynchronous circuit design.
- **Mapping from dataflow models to mesoscopic asynchronous models**: For quasi-delay-insensitive asynchronous circuits, built a mapping flow centered on C-Element-based asynchronous control units. Mapped dataflow-level components to “Sender–Relay–Receiver” mesoscopic structures and modeled the corresponding data paths, control paths, and acknowledgment mechanisms.
- **Hierarchical intermediate representation and automated conversion flow**: Designed XML-based intermediate representations for dataflow-level, mesoscopic-level, and gate-level conversion. Implemented graphical input parsing and automated transformation across hierarchical representations, enabling end-to-end automation of the synthesis flow.
- **Virtual circuit library and mapping rules for emerging processes**: Built a virtual circuit library covering basic logic gates, constant cells, and common asynchronous control units. Established binding rules from mesoscopic models to gate-level cells, supporting later adaptation to specific process libraries and integration with commercial EDA synthesis flows.

---

## RISC-V Matrix Computing SoC / TPU Matrix Acceleration Subsystem Research

**Project Source:** Subproject of a Major Science and Technology Project of Gansu Province  
**Project Date:** 2025-04 ~ 2026-03

This project focuses on the design and debugging of a RISC-V matrix computing SoC and TPU-based matrix acceleration subsystem for AI acceleration and matrix-intensive applications. The system integrates a laboratory-developed CPU core, on-chip NoC, TPU acceleration unit, on-chip memory, SPI, and other peripheral modules. The project implements system interconnection, cache architecture design, and FPGA board-level verification for matrix computing tasks, resulting in a commercially deliverable AI acceleration FPGA development board.

**Main Responsibilities:**

- **Matrix computing SoC architecture design**: Participated in the architecture design of the matrix computing SoC and designed a multi-level cache architecture to improve data reuse and support high-bandwidth memory access requirements.
- **Multi-level cache implementation and verification**: Completed RTL implementation, functional debugging, and simulation verification of multi-level cache-related modules, supporting data read/write operations, cache interactions, and continuous data supply during matrix computation.
- **TPU matrix acceleration subsystem integration**: Participated in TPU matrix acceleration subsystem integration, completing interconnection code development and system-level debugging among the self-developed CPU core, NoC, TPU, and on-chip memory.
- **Peripheral interface integration and board debugging**: Integrated SPI and other peripheral interfaces, completing interface adaptation, communication verification, and FPGA development board debugging between peripheral modules and the main SoC system.
- **FPGA system-level verification**: Completed system-level synthesis, board-level testing, and issue localization on the FPGA platform.

<img src="{{ '/file/TPU.jpg' | relative_url }}" alt="profile" class="floatpic">

