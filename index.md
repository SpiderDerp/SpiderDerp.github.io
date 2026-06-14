## About Me
Hi! My name is Sreeram Rave and I am currently studying Computer Engineering at the University of Illinois Urbana-Champaign.
My interests are Computer Architecture, FPGAs, ML, and Game Development.
[Resume](https://drive.google.com/file/d/15l9A53U-kVBQgVdUkQdVf1-tOFqvmeH5/view?usp=sharing)
## Projects
**<ins>2-Wide Out-of-Order RV32IM Processor</ins>**
Collaborated in a team of 3 to architect and verify a 2-wide superscalar out-of-order RV32IM processor with a speculative front-end (pipelined I-cache, stream-buffer prefetcher, GShare predictor, BTB, RAS) and a split LSQ with CAM-based memory disambiguation, synthesizing at 550 MHz and achieving up to 1.27 IPC.
**Made Using:** SystemVerilog

**<ins>FPGA Game Boy Advance Emulator</ins>**
Functionally-accurate GBA SoC on Spartan-7 with an ARM7TDMI CPU (VHDL) and original SystemVerilog subsystems for memory map, PPU, IRQ, timers, and cartridge/DDR interfaces, featuring multi-clock video/timing, a dual-port 240x160 framebuffer with HDMI scaling, and MicroBlaze USB HID keyboard input.
**Made Using:** SystemVerilog, VHDL, C

**<ins>Local RLHF Pipeline for Phi-3</ins>**
Fine-tuned a 3.8B-parameter Phi-3 model via end-to-end RLHF on Apple Silicon (MPS), training a custom Reward Model on a TruthfulQA-derived dataset and stabilizing a PPO loop with a hybrid device-offloading architecture for stable reward convergence.
**Made Using:** PyTorch, Transformers, TRL, Python
[View Here](https://github.com/SpiderDerp/rlhf-apple-silicon)

**<ins>FPGA Commodore 64 Emulator</ins>**
Cycle-accurate Commodore 64 FPGA SoC on Spartan-7 (xc7s50) integrating the 6510 CPU, VIC-II graphics, SID audio, and CIA peripherals, with multi-clock video infrastructure, dual-port framebuffer output, MicroBlaze USB HID input, and Python BRAM/ROM tooling for timing closure.
**Made Using:** SystemVerilog, VHDL, C, Python
[View Here](https://github.com/SpiderDerp/urbana-c64-emulator)

**<ins>BeatPeeler</ins>**
Android application to separate vocal and instrumental tracks using the REPET algorithm, evaluated with audio quality metrics including SDR, SIR, and SAR.
**Made Using:** Python, Java, C++

**<ins>4-Way Set-Associative Blocking Cache</ins>**
Synthesizable state-machined 4-way set-associative cache with a pseudo-LRU replacement policy, OpenRAM-generated SRAM hard IPs for data/tag arrays, and a SystemVerilog testbench using constrained random testing and covergroups for full coverage.
**Made Using:** SystemVerilog

**<ins>5-Stage Pipelined RV32I Processor</ins>**
Synthesizable 5-stage RV32I processor with full hazard detection, data forwarding, stall control, and branch flush logic, verified for ISA compliance with Spike RVFI, directed tests, and CoreMark, targeting 500 MHz-class timing.
**Made Using:** SystemVerilog, RISC-V

**<ins>RISC-V Operating System (Rizz-V)</ins>**
Custom operating system for the RISC-V architecture capable of running user-space applications such as a shell, DOOM, and other compatible games.
**Made Using:** C, RISC-V Assembly

**<ins>FPGA GameBoy Emulator</ins>**
Functional Game Boy emulator on the Spartan-7 FPGA written with SystemVerilog
**Made Using:** SystemVerilog, C

**<ins>Infinity Slime Dungeon</ins>**
A rogue-lite Idle RPG made for web browsers.
**Made Using:** C#, Unity
[View Here](https://antiveninstudios.itch.io/infinity-slime-dungeon)

**<ins>Tilt-Controlled Car</ins>**
A controller that can steer and accelerate a car by tilting it.
**Made Using:** TTL Chips, Gyroscope Chip, RPi Pico, Arduino IDE
[View Here](https://drive.google.com/file/d/107fnsYd8tKXBt2Vku7593nw2kLQ-Qgvp/view?usp=drivesdk)

**<ins>TImon</ins>**
A Pokemon Battle Engine that can run on a TI-84 Plus CE calculator
**Made Using:** C
[View Here](https://github.com/SpiderDerp/TImon)

## Contact Me
<srave2@illinois.edu>
