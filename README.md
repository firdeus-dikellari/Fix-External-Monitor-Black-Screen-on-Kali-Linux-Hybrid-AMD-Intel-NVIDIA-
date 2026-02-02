# Fix NVIDIA Black Screen on Kali Linux (Kernel 6.x, Hybrid Graphics)

A comprehensive guide to fix **black screen issues on Kali Linux 6.x** when using **NVIDIA GPUs on hybrid AMD/Intel + NVIDIA laptops**, especially when **external monitors** are connected.

This repository documents a reliable fix for boot-time display failures caused by integrated GPU drivers (`amdgpu` / `i915`) conflicting with the NVIDIA driver on hybrid graphics systems.

## Problem Solved
- Black screen on boot or login when external monitors are connected
- NVIDIA driver conflicts with integrated AMD or Intel graphics
- System hangs with ACPI or GPU initialization errors
- Graphical login only works after manually running `startx`

## Quick Start
Follow the **step-by-step fix guide** here:

➡️ [Fix NVIDIA Black Screen on Kali Linux 6.x (Hybrid Graphics)](Fixing-NVIDIA-Drivers-on-Kali-Linux-with-Kernel-6.x-Hybrid-Graphics-Laptops.md)

## Tested On
- **Laptop:** Lenovo Legion 5
- **GPU:** NVIDIA GeForce RTX 4060 Laptop
- **CPU:** AMD (hybrid graphics)
- **OS:** Kali Linux 2024.4
- **Kernel:** 6.17.10-kali-amd64

## Tags
`kali-linux` `nvidia` `black-screen` `hybrid-graphics` `external-monitor`  
`optimus` `prime` `amdgpu` `i915` `linux-troubleshooting`
