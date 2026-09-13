# OpenLane2 4-bit Counter

## Project Description

This project implements a 4-bit synchronous counter using Verilog HDL.

The design was processed through the OpenLane2 RTL-to-GDSII flow using the Sky130 PDK.

## Counter Operation

- The counter increases by one at every rising edge of the clock.
- When reset is active, the counter becomes zero.
- The counter output is 4 bits wide.

## Tools Used

- Verilog HDL
- OpenLane2
- Sky130 PDK
- Docker
- Ubuntu WSL2
- KLayout

## Project Files

- `counter.v` — Verilog source code
- `config.json` — OpenLane2 configuration
- `counter.gds` — Final layout file

## Results

The OpenLane2 flow completed successfully.

- DRC: Passed
- LVS: Passed
- Antenna Check: Passed

## Author

Shivanand
