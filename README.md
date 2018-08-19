# KeyBoard-Instrument-by-Arduino-
This is a very simple Piano (KeyBoard Instrument)using very simple components (Resistors || Buttons || Piezo)
The idea is that when you click one push button you close the circuit and let the current move throw specific resistance that gives you a specific note when you push another button the current moves in another lane in the circuite that gives you another note 
The code is very simple 
First I declare an array of four notes using different frequencies 
Then in my setup() I use the function Serial.begin();
In my loop() I declare a local variable to hold the value read on pin (A0)
Then I use an if() else statement I can use each value to a defferent tone and after each if() statement I call the tone function 
else to stop palying notes when there is no button being pressed call the noNote() function 
