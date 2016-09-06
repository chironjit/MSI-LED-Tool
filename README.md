# MSI-LED-Tool
This is a tiny project to allow modification of the LEDs of a MSI GTX 1080/1070 Gaming X card without the requirement of all the bloatware that the MSI tooling includes.

As of its original release it includes a fix color and the breathing mode. I mixed them up a bit and called it "Flashing" in this application. If you need the original Flashing mode or any custom mode and you aren't a developer, just create a new Issue describing the desired effect.

# Installation
* To install the tool you place the "MSI LED Tool" executable, the "Settings.json" file and the included "Lib" folder in whichever folder you desire to be its location.
* You have to point the path in the "regedit.reg" accordingly to your newly created and selected folder.
* Open the Settings.json file to change the R(ed), G(reen), B(lue) variables to your desired color scheme and toggle "EnableFlashing" accordingly if you desire the breathing animation. 
* Run the "MSI LED Tool" executable and if you like what you see, run the "regedit.reg" file to register the tool to startup upon Windows boot, after which it will automatically apply your configured settings.