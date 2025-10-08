# sky130B_setup
This repository provides a pre-configured SkyWater SKY130B PDK setup for use with tools like Magic, Xschem and Ngspice on WSL (Windows Subsystem for Linux) compatible with windows 11. It allows you to quickly start designing and simulating circuits without manually installing or configuring the full PDK environment.

# Download
The complete environment backup (.tar, ~13 GB) is available here:
https://drive.usercontent.google.com/download?id=1cXZe3tQ_Io8PHcMgZlaRMDMgs9vexHrn&export=download&authuser=0

# Quick Setup
1) Download the .tar file from the link above.

2) To import into WSL, open PowerShell(as administrator) and run (example _ imported to drive E):
                 wsl --import sky130B E:\sky130B_setup_backup C:\Users\YourName\Downloads\sky130B_setup_backup.tar

3) Verify import by running:
                 wsl -l -v
The sky130B instance should appear in the list.

4) Launch and enter your imported sky130B WSL environment:
                 wsl -d sky130B
You’re now inside your Linux system with the Sky130 setup ready to use.

# Included Components
1) SkyWater SKY130B PDK (130nm)
2) Xschem Schematic Capture
3) Ngspice Circuit Simulator
4) Magic VLSI Layout Editor
5) Pre-configured paths and environment setup

