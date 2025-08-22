# PICO 1V IS WIP

The PCB for Pico 1V is still in progress. Don't use it!

# Pico 1V

Pico 1V is an RP2040 board with the following additions/changes from the official Raspberry Pi Pico board:

* Switchable 1.8V/3.3V GPIO.
* A power LED.
* A reset button.
* A USB-C port instead of a Micro-B port.

Pico 1V is sill pin-compatible with the official Raspberry Pi Pico board, so you can use Pico 1V as a drop-in replacement for your existing Pico board.

## Acknowledgements

The schematic for Pico 1V was originally based on [Mitayi-Pico-D1](https://github.com/CIRCUITSTATE/Mitayi-Pico-D1), and the PCB for Pico 1V is from scratch.
Some of the components in the Pico 1V schematic are nearly unchanged from the Mitayi-Pico-D1 schematic.
Huge thanks to CIRCUITSTATE for open-sourcing Mitayi-Pico-D1, it was very helpful for this.

The voltage-switching implementation is based on the method described in [xenia's fantastic blog post](https://blog.awoo.systems/posts/2024-07-27-rp2040-low-voltage-operation).

## License

This project is licensed under the [MIT license](./LICENSE).
