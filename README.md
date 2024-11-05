# antenna-board

This repo contains the KiCAD files for the PROVES Kit Antenna Board. This board currently goes on the +Z endcap of the satellite and hosts the antennas, interfacing ports, and some other support circuitry!

## antenna_top_cap_board_v1a
This antenna board is a reformat of the V1 Antenna Board that consolidates a bunch of the 2pos Picolock and STEMMA connectors into a single connector that runs back to the V3b EPS Board. We are probably going to leapfrog this version to land on V2 which fundementally changes things about the antenna feed path. 

## antenna_top_cap_v2
This version of the antenna top cap featuers major changes to the antenna feed path and debug passthroughs. Notable features are as follows: 
- Updated Balun Part Number (no longer sucks! still sucks to solder though)
- Addition of 12-pos and 5-pos Battery Board and Flight Controller Board debug connectors.

