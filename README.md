<h1>Final Project : Automatic card dealer </h1>
<p>An automatic card dealer is a machine which can deal poker cards into 4 piles by activating  raspberry pi3. </p>
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
 
After you made the body, next we will have to build the circuit.</br>
The following is the gpio of raspberry pi3.</br>
![image](https://github.com/Jo-Yu/final-project/blob/master/raspberry-pi-15.jpg)</br>
To activate the stepper motors with raspberry pi3, we will have to connect the stepper motors to the gpio that can output 5V and ground.</br>

The following pictures show the circuit I connect. You can use them for reference.</br>
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

<ul>If you got them all right, you should be able to activate your stepper motors when you run the python script now.
	<li><h4>software</h4></li>
about the software, because we want to use websocket to start the machine by running python script, we will have to write a node.js script and a html script for creating a websocket ,and a python script to control the dealer machine. Of course there will also be a lot of different ways to complete this part.
</ul>
The following will be the scripts mentioned above:</br>
step3.python:



![image](https://github.com/Jo-Yu/final-project/blob/master/螢幕快照%202018-06-20%20%E4%B8%8B%E5%8D%885.16.43.png)</br>
![image](https://github.com/Jo-Yu/final-project/blob/master/螢幕快照%202018-06-20%20%E4%B8%8B%E5%8D%885.17.05.png)</br>
![image](https://github.com/Jo-Yu/final-project/blob/master/螢幕快照%202018-06-20%20%E4%B8%8B%E5%8D%885.17.31.png)</br>
![image](https://github.com/Jo-Yu/final-project/blob/master/螢幕快照%202018-06-20%20%E4%B8%8B%E5%8D%885.17.43.png)</br>
![image](https://github.com/Jo-Yu/final-project/blob/master/螢幕快照%202018-06-20%20%E4%B8%8B%E5%8D%885.17.54.png)</br>
And then it's the index.html file</br>
html:</br>
![image](https://github.com/Jo-Yu/final-project/blob/master/螢幕快照%202018-06-20%20%E4%B8%8B%E5%8D%885.19.00.png)
finally it's the webserver.js file</br>
node.js:</br>
![image](https://github.com/Jo-Yu/final-project/blob/master/螢幕快照%202018-06-20%20%E4%B8%8B%E5%8D%885.19.22.png)

<p>Now we are all set!  Lets start up the server and try if it's functional. But first please be sure the place you save your files doesn't make the system unable to work.</p>
The following pictures show where the files are saved:</br>

![image](https://github.com/Jo-Yu/final-project/blob/master/0.png)</br>
![image](https://github.com/Jo-Yu/final-project/blob/master/2.png)</br>
![image](https://github.com/Jo-Yu/final-project/blob/master/3.png)</br>

Now we are going to start up the server,please type these in your pi3 terminal:</br>
![image](https://github.com/Jo-Yu/final-project/blob/master/4.png)</br>
![image](https://github.com/Jo-Yu/final-project/blob/master/5.png)</br>

Open the browser at localhost 8080 port:</br>
![image](https://github.com/Jo-Yu/final-project/blob/master/6.png)</br>

Click the "click me" botton:</br>
![image](https://github.com/Jo-Yu/final-project/blob/master/7.png)</br>

<p>Here is a demonstration clip of it:</br>
https://drive.google.com/file/d/1LnXHMJXoDLYc3EFLGQ8kR4WPyOjZC1kC/view?usp=sharing</p>


<p>Now if you did all the things right, your automatic card dealer should be working finely! Thank you for watching!</p>









