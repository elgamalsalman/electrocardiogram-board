# ElectroCardioGram (ECG) Board &nbsp; ![Image of Version](https://img.shields.io/badge/version-v1.0-green) ![Image of Dependencies](https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen)

### Description

This is a pcb board designed, printed and even soldered from scratch with the purpose of plotting my heart beats on an oscilloscope. The final product and the final oscilloscope plots are shown below.

<p align="center">
  <img src="./assets/board_soldered.jpg" alt="final board" width=500 />
  <img src="./assets/ecg_graph.jpeg" alt="ecg oscilloscope plot" width=500 />
</p>

I am alive haha.

This entire project was built using Altium Designer.

### Circuit

The circuit is mainly a signal processing circuit, so it consists of an instrumentational amplifier for signal amplification with a drl circuit for noise reduction, after which there are two other stages of signal cleaning: band pass filter and notch filter (to block the AC power frequency noise). Also the circuit includes a capacitor bank that are charged by the batteries and discharge in spikes of current for smooth operation, and a lot of connectors to disconnect and connect every part of the circuit for testing and visualising the contribution of each part of the circuit. The circuit schematic can be seen below.

<p align="center">
  <img src="./assets/schematic.png" alt="schematic" />
</p>

### PCB

Then on altium the pcb was made to be compact and use as few vias as possible.

<p align="center">
  <img src="./assets/pcb_1.png" alt="pcb" />
</p>

### Soldering

Then the surface-mount soldering took place using a microscope-equiped soldering station and the main two soldering methods were practiced: using soldering wire and using solder paste.

<p align="center">
  <img src="./assets/soldering_station.jpeg" alt="soldering station" width=300 />
</p>

Giving our final product shown below once more!

<p align="center">
  <img src="./assets/board_soldered.jpg" alt="final board" width=500 />
</p>
