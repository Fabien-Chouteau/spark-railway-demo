# SPARK Railway Demo

This demo simulates a railway network with trains, switches and signaling. The signaling system is proven with SPARK to ensure that trains cannot collide.

![Screenshot](screenshot.jpg?raw=true "Screenshot")

## Build Instructions

- Make sure to get all the Git submodules "$ git submodule update --init --recursive"
- Download and install the compiler: [GNAT for ARM package](http://libre.adacore.com/download/configurations)
- Start GPS (GNAT Programing Studio)
- Open the project file spark_railway_demo.gpr
- Use the "Build all" button to compile
- use the "Flash to board" button to program the STM32F429 Discovery board
