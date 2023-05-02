Download Link: https://assignmentchef.com/product/solved-cpe301-lab-08-atmega-analog-to-digital-converters-by-initializing
<br>
To learn how to program the ATmega Analog to Digital Converters by initializing and using the appropriate special function registers. You will develop two functions, <em>adc_init</em>, and <em>adc_read</em>, and a program which uses the two functions to read analog data from a photoresistor and sends the data over serial to a PC.

<strong><em>Procedure</em>:</strong>

<ol start="3">

 <li>Read chapter 8 of the textbook and browse section 26 of the Atmel 2560’s datasheet, paying extra attention to sections 26.2, 26.3, 26.4, and 26.8.</li>

 <li>Write two ANSI C functions:

  <ol>

   <li>void adc_init( ) – Initializes the Analog to Digital Converter to be ready to read analog data.</li>

   <li>unsigned int adc_read(unsigned char adc_channel) – Returns the analog data read from the analog channel given as a parameter.</li>

  </ol></li>

 <li>Connect a photoresistor and an axial resistor in series as a voltage divider and write a program which reads the analog voltage of the divider and sends the voltage values over serial to your PC. Use the Arduino IDE’s Serial Plotter to plot the voltage values.</li>

 <li>Modify the program to turn on the on-board LED when the light level is above some threshold. <strong><em>Notes</em>:</strong></li>

</ol>














