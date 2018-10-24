<!--
Title: RGB amplifier
Description: RGB amplifier used with Arduino or Raspberry Pi to control 12v LED light strips.
Author: Gunnar Bjorkman
-->

<h3>RGBamp</h3>

This project ties in nicely with https://github.com/Gunnthorian/homebridge-pwmhat my homebridge smart home program

<h4>This is an open source hardware project -- RGB amplifier 0-5v to 0-12v</h4>

Designed by Gunnar Bjorkman

<h4>About</h4>
This is a small project that I wanted to work on, I use a perma-proto board from this design currently to control my RGB light strip on my desk. Here is an opensource schematic of the board for anyone to use and manufacture themselves (I used PCBway.com, it was a total of $18 to get 10 of the bare boards made and shipped to my house)

<h4>Purpose</h4>
This RGB amplifier is great for Arduino projects and can be used with Raspberry Pi projects, for a Pi you just need to use a pwm hat to output the 5v signal needed to get the brightest lights (this is what I do).

<h4>Usage</h4>
The board takes 3 signal wires in (RGB 0v-5v), 1 GND from the source of the signal wires, and 12v power supply. The outputs are +12v and RGB -12v (proportinal to the RGB signal wires).

<div style="height:500px">
  <img src="https://raw.githubusercontent.com/Gunnthorian/RGBamp/master/schematic.png" width="250" style="float:left">
  <img src="https://raw.githubusercontent.com/Gunnthorian/RGBamp/master/board.png" width="250" style="float:left">
  <img src="https://raw.githubusercontent.com/Gunnthorian/RGBamp/master/render.png" width="250" style="float:left">
</div>
<br>
<div style="width:500px">
  BOM:
  <li>3 -- 330Ω resistors</li>
  <li>1 -- 16v 220µf capacitor</li>
  <li>1 -- 12v power jack <a href="https://www.sparkfun.com/products/119">link to part on Sparkfun's site</a></li>
  <li>2 -- 4 pin headers (preferably 90°)</li>
  <li>3 -- TIP31C mosfet transistors</li>
  </div>
