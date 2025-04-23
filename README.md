A program to take screenshots (screenshots): of the entire screen, a selected part, an active window. For Windows with open source code.

#Screenshot #Screenshot #ScreenPhoto #ScreenShot



Working with the command line.

The command line with parameters is needed to take a picture of the screen without turning on the kuss program window, i.e. kuss.exe is launched without a window, takes a picture of the specified, closes without remaining in the RAM. Thus, using the command line with parameters, kuss.exe can be used: 1) as an external screenshotter, giving it commands from another program, 2) take screenshots using global hot keys - read more in the chapter below.

Parameter #0: Full path to kuss.exe - enter only this in the command line and press Enter: the program starts, showing its main window. If you specify other parameters in the command line in addition to parameter #0, the program will start non-visually (i.e. without displaying the main KUSS window) and then take a photo and save the screenshot as you specify in parameters #1 and #2:

Parameter #1: Photographed area: "0" - the entire screen, "1" - the selected area, "2" - the active window, "3" - the element.

Parameter #2: Path and format of the screenshot file. A screenshot taken in invisible mode will be saved to the path specified in this parameter #2. The file format is determined by the specified extension: png or jpg - only these formats are supported. If parameter #2 is not specified, the screenshot will be saved to the current user desktop as "Screenshot.png". If the screenshot folder specified in parameter #2 does not exist, then this folder will be created automatically using the ForceDirectories method, i.e. with all parent and child folders specified in the path.

Examples of command lines in KUSS invisible mode:

Shot of the entire screen with saving to drive D:

"kussPath\kuss.exe" "0" "D:\Screenshot.png"

If the output folder is not specified, the file is saved to the desktop:

"kussPath\kuss.exe" "0" "Screenshot.png"

If the file extension is not specified, then by default it is saved in png:

"kussPath\kuss.exe" "0" "Screenshot"

If parameter #2 is not specified at all, then Screenshot.png will be saved to the desktop:

"kussPath\kuss.exe" "0"

If the jpg extension is specified in parameter #2, then the file will be saved in this format:

"kussPath\kuss.exe" "0" "D:\Screenshot.jpg"
