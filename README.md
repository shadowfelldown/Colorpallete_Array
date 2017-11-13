# Colorpallete_Array
A repository to store the resolume configuration files and instructions for driving an array of colorpalletes.
## Installation
1. Backup contents of resolume folders
2. paste all the stuff in resolume files folder for the verison of resolume that you are running into your resolume folder
3. Ensure that the following are in your resolume folders:
	2.1. The following files should be in the resolume files\fixtureLibrary folder:
		2.1.1. Chauvet Colorpallete01.xml 
		2.1.2 Chauvet Colorpallete02.xml
	2.2.The following files should be in the resolume files\preferences folder:
		2.2.1. dmx.xml
	2.3. The following files should be in the resolume files\presets\screensetup folder:
		2.3.1. COLORpallete_Array.xml
	2.4. The following files should be in the resolume files\compositions folder:
		2.4.1.COLORpallete_Array.avc
		
	
4. Open "COLORpallete_Array.avc"
5. in advanced mapping window, load COLORpallete_Array.xml as preset
6. In preferences window, ensure that lumiverses are set to universe 0
## Running
1. Connect to Enttech.
2. Set static IP on computer
3. disable Wifi.
4. open COLORpallete_Array.avc
5. Adjust the Brightness of the fixtures so that they are uniform across all colorpalletes, as each light has variable brightness of various colors.

## Tips
to see how a pattern looks on the colorpallets, open advanced mapping window. Pallet sections illuminate when average area is activated.

## Adding Additional Colorpalletes to setup
For each colorpallete fixture there should be 8 total fixtures created in the advanced mapping with a total of 27 DMX channels per fixture.
1x - Chauvet Colorpallete01 |ch 1-ch6|
7x - Chauvet Colorpallete02 |ch 7,8,9| |ch 10,11,12| ... |ch 25,26,27|
Easiest way to add colorpalletes is to drag select around one of the existing colorpallete fixtures and alt-drag the fixtures to a new location.
