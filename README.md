# Balanced Homodyne Photodetector

This repository contains the design, simulation, fabrication, and measurement files for a balanced homodyne photodetector developed for quantum optics experiments.

## Final Designs

The completed detector designs are stored in `final_designs/`:

- `Photodetector_v2_3_HI.asc` — final high-gain design
- `Photodetector_v2_3_LO.asc` — final low-gain design

Both schematics share the custom LTspice symbols and models stored in the same directory.

## Measured Performance

- High-gain configuration: approximately 36 dB gain
- High-gain shot-noise separation: approximately 25 dB
- Low-gain configuration: approximately 30 dB gain
- Low-gain shot-noise separation: approximately 12 dB
- Measured bandwidth: approximately 70 kHz to 10 MHz

## Repository Structure

```text
final_designs/         Completed high- and low-gain LTspice designs
experimental/          Incomplete design explorations
archive/               Earlier design revisions and legacy experiments
pcb/                   Fabrication outputs, CAD files, BOMs, and Gerbers
measurements/          Analysis scripts, measurement data, and plots
docs/                  Documentation images and figures
