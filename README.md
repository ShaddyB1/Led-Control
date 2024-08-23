LED Control Project
This project demonstrates various LED control patterns using an AVR microcontroller (assuming Arduino board). It includes functions to control individual LEDs, create an SOS pattern, adjust LED brightness using PWM, and create a pulsing effect.
Prerequisites

AVR microcontroller (e.g., Arduino board)
4 LEDs connected to the appropriate pins
Required libraries: avr/io.h, avr/interrupt.h, util/delay.h

Installation

Connect the LEDs to the microcontroller pins as specified in the code.
Upload the code to your AVR microcontroller using a compatible IDE (e.g., Arduino IDE).

Usage
The code provides several functions to control the LEDs:

led_state(uint8_t LED, uint8_t state): Turns a specific LED on or off.
SOS(): Creates an SOS pattern using the LEDs.
glow(uint8_t LED, float brightness): Adjusts the brightness of a specific LED using PWM.
pulse_glow(uint8_t LED): Creates a pulsing effect on a specific LED.
light_show(): Performs a predefined light show sequence.

To use a specific function, uncomment the corresponding function call in the main() function.
Configuration

F_CPU: Set the CPU frequency of your microcontroller.
PRESCALE_DIV1 and PRESCALE_DIV3: Prescaler values for Timer 1 and Timer 3, respectively.
PWM_PERIOD: Period of the PWM signal.

