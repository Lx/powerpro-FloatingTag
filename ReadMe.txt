¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯
Floating Tag
¯¯¯¯¯¯¯¯¯¯¯¯
Version 1.0
Sunday, 30 November 2003
________________________________________________________________________

What?
¯¯¯¯¯
The Floating Tag kit allows you to minimise as many as ten windows at
once, to small draggable ‘tags’ on screen. Once a window has been
minimised to this tag form, it no longer appears on the taskbar.
________________________________________________________________________

Requirements
¯¯¯¯¯¯¯¯¯¯¯¯
This kit uses the Win plugin, which is included with PowerPro.

The ‘Use Quote for Escape in Expression Strings’ checkbox, found under
Setup > Advanced Setup > Characters, must be ticked for the script to
work. This option is not ticked by default.
________________________________________________________________________

Automated Installation
¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯
Extract the contents of the archive into a temporary folder and double-
click the Install script. PowerPro must be running in order to do this.

The installation script will attempt to detect the current configuration
and assume that you would like to install the Floating Tag kit to this
.PCF file, but you have the option of selecting your own .PCF file
during the installation.
________________________________________________________________________

Manual Installation
¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯
If the automated installation procedure does not work for you:

1. Extract the ‘FloatingTag.PowerPro’ and ‘Import.txt’ files to your
   Scripts folder (generally ‘C:\Program Files\PowerPro\Scripts’).

2. Create a new folder named ‘FloatingTag’ within your Skins folder
   (e.g. ‘C:\Program Files\PowerPro\Skins\FloatingTag’).

3. Extract the ‘Back.bmp’ and ‘Skin.txt’ files to this newly created
   folder.

4. Open PowerPro Configuration, click the ‘Import from Text’ button
   found on the Setup tab, navigate to your Scripts folder (if PowerPro
   has not already placed you there), double-click the ‘Import.txt’ file
   and click OK to close PowerPro Configuration.

5. Delete the ‘Import.txt’ file from your Scripts folder.
________________________________________________________________________

Invoking
¯¯¯¯¯¯¯¯
Minimising a window to a tag involves a script call with a caption list
as a parameter:

.FloatingTag("Caption List")

Floating Tag will minimise the first window to match the caption list.

The suggested methods of invoking are .FloatingTag("Active") for
keyboard shortcuts and .FloatingTag("Under") for mouse actions.
________________________________________________________________________

Usage
¯¯¯¯¯
A tag consists of a ‘grip’ area and the tagged window's program icon.

* Left- or middle-clicking the grip allows you to reposition the tag on
  the screen.

* Left-clicking the icon will restore the window to its original form.

* Middle-clicking the icon will transfer the tag to the system tray.
  This is equivalent to PowerPro's *Window TrayMin feature.

* Right-clicking either the grip or the icon presents a popup menu that
  allows you to restore the window, transfer it to the system tray, and
  close the tag without restoring the window.

Tags will automatically disappear if their corresponding window closes
or reappears as a standard window.
________________________________________________________________________

To Conclude
¯¯¯¯¯¯¯¯¯¯¯
I'd really like to know if you need any help with this kit, or if it
grows on you, so please feel free to Email me with any questions or
comments that you may have. My Email address can be found through the
PowerPro Yahoo! group, at:

> http://groups.yahoo.com/group/power-pro/

...or you can just leave a message at the Group -- there's a good chance
that I'll see it just as quickly.

Thanks to David Troesch for testing, and to Pi and Keno for coming up
with the original idea and implementations.

Best regards,
Alex Peters
________________________________________________________________________

Version History
¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯
v1.0 (30/11/2003)
* Initial Release
________________________________________________________________________
