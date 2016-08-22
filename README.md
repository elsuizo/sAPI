# sAPI library for microcontrollers

This library implements a simple API that acts as a HAL (Hardware Abstraction
Layer) for microcontrollers.

It takes ideas from *Wiring library*, but use the concept of *peripheral* instead
the concept of *pin*, making the API regardless of the number of pins that use
certain peripheral.

## Documentation

### Included modules

**Internal Peripherals**

- Data types.
- Peripheral Map.
- ISR Vector.
- Board.
- Tick.
- Delay.
- Digital I/O.
- Analog I/O.
- UART.
- I2C.
- RTC.
- PWM.

**External Peripherals**

- Angular Servo (0 to 180°).
- Magnetometer (compass) sensor HMC5883L.

Every module includes an example.

### Software layers

![ "sapi-modulos-capas.png" image not found](docs/assets/img/sapi-modulos-capas.png "Modules an layers of sAPI library")

### Boards

Now available for boards:

- EDU-CIAA-NXP (NXP LPC4337 microcontroller). [Download documentation.](docs/assets/pdf/EDU-CIAA-NXP_Pinout_A4_v4r3_ES.pdf)
- CIAA-NXP (NXP LPC4337 microcontroller).
