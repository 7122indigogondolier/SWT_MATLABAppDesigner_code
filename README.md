# Stationary Wavelet Transform Application for Electrical Signal Analysis

**Summer Engineering Research 2019 (Colon Crew v2)

Colon Crew v2: Beth Reed, Jack Robey, Jeremy Wharton, Riwaj Shreshtha, Utkrist P. Thapa 
Supervisor: Prof. Erickson 

Washington and Lee University**

## Getting Started
 
1. Enter value in 'Resolution' Numeric Field (top left): 
	-Enter the sampling resolution in which the data file has been recorded
	-100 Hz by default (100 samples per second) 
	-Data file in use might have been downsampled to 20 Hz or 10 Hz so enter the resolution appropriately 

2. Press 'Load Data File' button and browse to the data file 

3. Wait for the 'Data File Loaded' lamp to turn green from blue 
	-100 Hz file takes longer than 10 or 20 Hz so might have to wait a few seconds 

4. Press 'Plot' or 'Plot Entire Length' button
	-'Plot' button plots the signal according to the default/entered values in the 'Signal Start Time' and 'Signal Length (Samples)' edit fields 
	-'Plot Entire Length' plots the entire signal length in a given channel 

5. Choose channels from the 'Channel' drop down
	-Press 'Plot' or 'Plot Entire Length' button after making a change to observe the change in the graph

6. Press 'Perform SWT' button to see the isolated levels in the signal
	-PREREQUISITE: The signal length (in number of samples) MUST be divisible by 2^15 so choose a proper signal length and plot the Original Signal first
	-This is because the swt function has been implemented by passing parameter N = 15 (levels of Stationary Wavelet Transform)
	-The lamp turns green once it's plotted the signal 
	-If a wrong signal length is used, the app will display an error message and return the signal length to its default value (2^15 = 32768 samples)

7. Choose the levels you want to view in the 'Levels' dropdown: 
	-Press the 'Perform SWT' button after making changes to 'Levels' dropdown to see changes 
	-Levels value is '9-11' by default meaning its showing us 9, 10 and 11 swt levels 
	-Maximum is '9-13' for our purposes since these levels correspond to the frequency of the CMPs we want to observe

Happy Signal Processing! 

## Author 

Utkrist P. Thapa '21 
**Summer Engineering Research
Washington and Lee University**
LinkedIn: www.linkedin.com/in/utkrist-thapa-13a035158


	
