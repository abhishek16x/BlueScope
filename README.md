# BlueScope
So this is basically a virtual Bluetooth based oscilloscope for real time signals using MATLAB. I have developed an embedded 
device which simply accepts an analog signal and converts it into equivalent digital bytes (Using ADC) and then then transmits
these bytes via Bluetooth to a device(Provided the device should have a bluetooth connectivity). I am accepting these bytes using 
the Bluetooth functionality of MATLAB. And then further plotting the original wave and processing exactly the way a conventional
benchtop oscilloscope would do. So far, I have been able to plot the correct frequency and amplitude of the waveform and embed it into a simple app using the MATLAB GUI.
But what I am not able to come up with is code or rather loop which will accept new samples, plot them and then discard them contionuously in a loop. Along with the shift of origin. 
And then what I am not able to do is the scaling of the X-axis and Y-axis. Like, I need a slider or a knob by varying which I can change the dimensions of my axes. 
And then also a simple push button named 'Hold' using which I can pause the loop and display the recent waveform standstill.
