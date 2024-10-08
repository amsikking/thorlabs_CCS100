# thorlabs_CCS100
Python device adaptor: Thorlabs CCS100 compact spectrometer, 350-700nm.
## Quick start:
- Install the 'ThorSpectra' GUI (from Thorlabs) and check the spectrometer. It should be 
straightforward to run the GUI and take a spectrum (GUI version 3.31.0.2062 used here).
- The GUI should install the essential drivers and .dll file onto the system path (a version included here for convenience "TLCCS_64.dll")
- Download and run "thorlabs_CCS100.py" for Python control.

![social_preview](https://github.com/amsikking/thorlabs_CCS100/blob/main/social_preview.png)

## Details:
- This adaptor was generated with reference to the "TLCCS.html" manual that was installed by the GUI at location:
  - C:\Program Files\IVI Foundation\VISA\Win64\TLCCS\Manual
- The essential "TLCCS_64.dll" file was found here:
  - C:\Program Files\IVI Foundation\VISA\Win64\Bin
