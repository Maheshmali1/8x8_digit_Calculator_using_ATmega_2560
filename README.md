# 8x8_digit_Calculator_using_ATmega_2560
This project is made to perform 8x8 digit basic math calculations using ATmega 2560 chip and written source code in Embedded C with Hardware abstraction style of coding.

Problem statement:
Calculator program : 

- Line One problem
- Line Two Answer.
Line 1 - Examples:
  789+876,
  9546-89,
  8765438*678,
  8765/76,
  In the case of Divider Quotient adn remainder need to display side by side.
  100/30 then the answer should be 
  3 10  - 3 is Quotient and 10 is remainder. 
  
  
Procedure Used :
1) For this project I have used the basic architecture view of ATmega 2560 chip to use the genral input / output pins.
2) For GPIO I have used the A, C, K and F ports of ATmega 2560 Chip.
3) After it I wrote the driver code for LCD and Calculator Keypad.
3) Then I used the function modeling style to write the various operations required to performn desired tasks.
4) At last I simulated the Source code with WOkWI online simulator and got the required results.

WOKWI simulation link to project : https://wokwi.com/arduino/projects/313411629111837248
