# Hello there 👋 I'm Mateusz

I'm currently working on embedded systems that combine **FPGA**, **MCU** and **Linux** platforms.  
Most of my interests revolve around **digital signal processing**, **real-time data pipelines**, and **low-level hardware interfaces**.

Right now I'm building an end-to-end DSP pipeline using:
- **Intel MAX10 FPGA** (FIFO + 32-bit FMC interface)
- **STM32H745** (MDMA ping-pong + lwIP raw UDP)
- **NXP i.MX8M Mini** (Linux/Yocto + real-time plotting on panel)

The idea is simple: create a small, open embedded system that moves raw DSP data from FPGA to Linux in real time, over Ethernet, and visualize it for further processing.  
This setup is a base for more advanced experiments with FFT, filtering, radar-style visualizations and embedded data acquisition.

I enjoy:
- experimenting with FPGA (even simple block-design/Qsys workflows)
- pushing MCUs to their limits (DMA, buses, networking)
- running Python tools on embedded Linux
- building complete pipelines end-to-end

More projects and documentation are on the way — stay tuned 🚀
