# final-project
<h2>Final Project : Automatic card dealer </h2>
<p>An automatic card dealer is a machine which can deal poker cards by activating  raspberry pi3. </p>
<h3>what you will need</h3>
<ul>If you want to build an automatic card dealer, you will need to prepare these following things first.
	<li>Raspberry pi3 model B</li>
	<li>digital SD card</li>
	<li>ARDUINO ULN2003+ Stepper motor (5V) x2</li>
	<li>Several DuPont lines</li>
	<li>A breadboard</li>
	<li>Cardboard</li>
	<li>a deck of cards</li>
	<li>some paperclips</li>
	<li>some other complements</li>
</ul>
<h3>Start to build the machine</h3>
<ul>After preparing what we will need for the project, we are ready to start!</br>
Now the following content will be divided into 2 parts, which are hardware and software respectively.
  <li><h4>hardware</h4>
  	About the hardware, we will have to create a machine to put your poker cards in first. I only made some change based on the poker card’s box, but you can also do it in lots of different ways since it is a little unstable using cardboard as the body of the machine. </ul>
The pictures below is the actual appearance of the machine body I made.

Front:
 ![image](https://github.com/Jo-Yu/final-project/blob/master/IMG_9857.JPG)
Left side:
 ![image](https://github.com/Jo-Yu/final-project/blob/master/IMG_9858.JPG)
Right side:
 ![image](https://github.com/Jo-Yu/final-project/blob/master/IMG_9860.JPG)
Back:
 ![image](https://github.com/Jo-Yu/final-project/blob/master/IMG_9859.JPG)
Top:
 ![image](https://github.com/Jo-Yu/final-project/blob/master/IMG_9861.JPG)
Bottom:
 ![image](https://github.com/Jo-Yu/final-project/blob/master/IMG_9862.JPG)
 
<p> After you made the body, next we will have to build the circuit.</br>
The following is the gpio of raspberry pi3.
![image](https://github.com/Jo-Yu/final-project/blob/master/IMG_9862.JPG)


To activate the stepper motors with raspberry pi3, we will have to connect the stepper motors to the gpio that can output 5V and ground.</p>
The following pictures show the circuit I connect. You can use them for reference.
Stepper motor for dealing cards (upper one):
![image](https://github.com/Jo-Yu/final-project/blob/master/IMG_9863.JPG)
![image](https://github.com/Jo-Yu/final-project/blob/master/IMG_9864.JPG)
Stepper motor for changing angles (downer one):
![image](https://github.com/Jo-Yu/final-project/blob/master/IMG_9865.JPG)
![image](https://github.com/Jo-Yu/final-project/blob/master/IMG_9866.JPG)
Breadboard:
![image](https://github.com/Jo-Yu/final-project/blob/master/IMG_9867.JPG)
Raspberry pi3:
![image](https://github.com/Jo-Yu/final-project/blob/master/IMG_9868.JPG)

