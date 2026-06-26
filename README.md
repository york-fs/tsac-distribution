# TSAC Distribution Board

![Revision](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fyork-fs.github.io%2Ftsac-distribution%2Finfo.json&query=%24.revision&label=Revision)
![Pad Count](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fyork-fs.github.io%2Ftsac-distribution%2Finfo.json&query=%24.pad_count&label=Pad%20Count)
![Via Count](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fyork-fs.github.io%2Ftsac-distribution%2Finfo.json&query=%24.via_count&label=Via%20Count)
![ERC Status](https://img.shields.io/endpoint?url=https%3A%2F%2Fyork-fs.github.io%2Ftsac-distribution%2Ferc.json)
![DRC Status](https://img.shields.io/endpoint?url=https%3A%2F%2Fyork-fs.github.io%2Ftsac-distribution%2Fdrc.json)

The TSAC distribution board is the interface between the PCBs inside the TSAC and the rest of the LVS. It connects to
the rear distribution via a 23-pin AMPSEAL connector and connects primarily to the BMS, IMD, and precharge PCB inside of
the TSAC. It also provides split termination for the CAN bus.

[Latest Release](https://github.com/york-fs/tsac-distribution/releases/latest)
[Interactive BOM](https://york-fs.github.io/tsac-distribution/ibom.html)

![Render Preview](https://york-fs.github.io/tsac-distribution/render.jpg)

## Cloning

A recursive clone must be used to download the `kicad-library` repository:

    git clone --recursive https://github.com/york-fs/tsac-distribution.git
