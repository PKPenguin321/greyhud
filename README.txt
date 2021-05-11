Fork of greyhud that incorporates votehud_custom_font for better bot kicking: https://github.com/andy013/votehud_custom_font

If you just want to use the HUD and play immediately:

1. Extract the "greyhud-master" folder located inside the "greyhud-master" ZIP folder.

2. Drag and drop that file to your custom folder located at "Program Files or Program Files (x86)/Steam/steamapps/common/Team Fortress 2/tf/custom" if you're on Windows.

3. If you don't like the health and ammo positions, try setting cl_hud_minmode to 0/1 in the console and their positions will move further/closer to the crosshair. The console can be accessed by hitting the ~ key on your keyboard, right under the Esc key. The console can be enabled by navigating to the main menu, clicking on options, clicking "Advanced...", and ticking the box that says "Enable developer console".

	
For customization options:
	
1. Drag and drop the "resource" folder located at "greyhud/Customizations/[the option that you want]" to the main "greyhud" folder. If done correctly, this should replace several files.

2. If you want custom fonts, download them by going to "greyhud/resource/font", right click them all, and click "Install" if you're using Windows 7 or higher. To preview fonts, go to "greyhud/resource/font", and double click the files to see how they'll look in-game.


For custom crosshairs:

All custom crosshairs can be found at "greyhud/scripts/hudlayout.res" at the top of the file. This file can be opened with Notepad or Notepad++ for the simplest editing.

1. To edit the visibility of a crosshair, change the number to the right of "visible" as well as "enabled" to "1" instead of "0" for the specific crosshair you want.

2. To edit the size, change the name of the font by increasing or decreasing the number after "size". Since this method involves hard-coding the specific sizes, some numbers will not work.

3. To edit the position, change the "xpos" (horizontal position) and "ypos" (vertical position) and type "hud_reloadscheme" into the in-game console to see your changes. Remember, the positions of the crosshairs might not be perfect for everybody, so you may need to change the xpos/ypos to get the best result for you.

4. To edit the color, change the "fgcolor" to the RGBA color code that you want. The first number is the intensity of Red, the second is Green, the third is Blue, and the fourth is the alpha (how intense it is overall). All these numbers range from 0 to 255, 0 being the darkest, and 255 being the brightest. Common RGBA color codes can be found on many websites if you need further assistance.
	
Credit goes to broeselhud_blue for the crosshair font files and code.

Feel free to message me on Steam @ https://steamcommunity.com/id/sAvenisgrey.