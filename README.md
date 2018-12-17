# embeddedDevices

This is for my project, System of Sounds. There are two main files here. 

One is a publish file where it publishes light values into the cloud 
There other is a subscribe file where it listens to the cloud and controls the LED according to the cloud values. 
There is a second subscribe file called subThread where it allows you to use multiple PINs on the ESP32, but it starts
nesting functions which causes it to crash.

