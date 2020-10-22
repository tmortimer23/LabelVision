# Label Vision

LabelVision is a photo and video annotation tool used to identify people and track their movement from frame to frame. The goal is to use these annotations as an input for a machine learning algorithm to be able to annotate videos automatically. 

## Installation

1. LabelVision requires Python 3.6 or greater. This can be downloaded from the [Python downloads page here](https://www.python.org/downloads/). It is recommended that you install Python 3.9.0.  

2. After downloading the correct version of Python for your system, the executable should be run. A window will appear that will ask if you would like to install Python to your machine. For simplicity, click install and keep the installation in the default directory. 

3. Following the installation, a window should appear saying "Setup Successful". To check if Python installed correctly, open your command window and type:  	 
	
		python3 --version 

	The installed Python version should appear on the next line. If you have trouble installing Python correctly, follow the links posted below for information according to your system. 

	[Windows](https://www.youtube.com/watch?v=i-MuSAwgwCU&ab_channel=IDGTECHtalk) 

	[Mac](https://www.youtube.com/watch?v=TgA4ObrowRg&ab_channel=AutomationStepbyStep-RaghavPal) 

4.   Following the installation of Python, it is required that you install the Pillow module via the command line. To do this, bring up your command line and type the following: 
	
		pip3 install Pillow

5. With Python and Pillow installed, you can now download and use LabelVision. (Not sure about the specific download and installation of this program)

6. After downloading the 3 files necessary to use LabelVision, you should consolidate them into a single folder that is easily accessible. 

7. To launch the program, select the file main.py and choose the option to edit with IDLE (whatever version you have). Following this, use F5 or the "run module" option under the "Run" tab to launch LabelVision. 



##Usage

Using LabelVision is actually quite simple and there are a minimal amount of controls.  

The first step in using the program to annotate video is selecting your directory. Go to "File" -> "Open Directory" in the top left.  

Choose the directory (most likely a photo set) that you would like to annotate. 

Once you have opened your image directory in LabelVision, the first frame in the set should appear on the screen. 


##Shortcuts and Hotkeys

(Perhaps insert the image for the hotkeys here)

![Drag Racing](testimage.jpg)

W - with the W key, you can switch between creating annotations by dragging your mouse (the pointer color will be black) and deleting annotations by simply clicking on it (the pointer color will be red in this mode).

A/D - A and D are used to move to the previous frame and next frame in the photo set, respectively. 
