# Class-A-Amplifier-Interface

This project provides a GUI with functionalities for a Class-A Amplifier, made in Matlab. 

Design specifications:
-vBE,on=0.7V;
-IBias=0.2A;
-RL=60Ω;
Requirements: 
-draw VTC vO(vI) and indicate the transistor state (off, aF, exc) for every region of VTC;
-consider vI=0.7V+6sin(wt)[V], draw the waveforms for vO(i), iO(t), vCE(t) and iC(t) and specify the peak values for the signals;
-calculate the average value of the power dissipated by the load and average efficiency for vI=0.7V+0.6sin(wt)[V];
-explain why the average efficiency is less than the maximum average efficiency possible for this stage.

For this project “Class A amplifer” I chose to make a nice Matlab interface which shows the plots for the RLOAD, Vout, Vi, Vc, Io and Ic. The values for the 2 input voltages (Vsat and Vcc) can be changed from the edit boxes. The interface contains also action buttons which allow us to plot the signals. I want to improve my GUI and I put on it the option for make the plot on the axes visible and invisible, and I put a background image on it. The results I obtained through the GUI created meet my expectations, being correct and respecting the theoretical calculation. And just for fun, I want to show you how to manipulate the mouse pointer. The last push button (Something Interesting) opens another GUI (I wrote a specific function for this GUI) where there is a push button to close it, but you can not do that because the mouse pointer will go somewhere at random when you try to press it, so to close the figure, use the window ordinary x in the upper right corner.
