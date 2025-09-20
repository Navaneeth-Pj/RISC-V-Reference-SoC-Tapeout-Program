# RISC-V-Reference-SoC-Tapeout-Program
This repository contains my weekly updates of "RISC‑V Reference SoC Tapeout Program". The topics are organized by weekly, and you can click on each heading to expand and see more details.
<details>
<summary><b>Week 0 - Tools Installation</b></summary>
<br>
Yosys Installation
<br>
Here are the commands to install Yosys
<br>
$ sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make (If make is not installed please install it)
$ sudo apt-get install build-essential clang bison flex \
 libreadline-dev gawk tcl-dev libffi-dev git \
 graphviz xdot pkg-config python3 libboost-system-dev \
 libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
$ make
$ sudo make install

