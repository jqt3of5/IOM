# IOM
A library to perform PWM using Integer Overflow Modulation

on a value line MSP430, it only has a 16MHz clock frequency. This means that in order to do a 3 channel PWM the PWM period would be way too long, and cause flickering in lights. As a result, I invented a different way to do it, called IOM. This allows the frequency to be significantly higher on slower clock speeds. 
