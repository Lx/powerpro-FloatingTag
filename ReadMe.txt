¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯
Floating Tag
¯¯¯¯¯¯¯¯¯¯¯¯
Version 2.1
Tuesday, 5 October 2004
________________________________________________________________________

What?
¯¯¯¯¯
The Floating Tag kit allows you to minimise any amount of windows to
small draggable ‘tags’ on screen. Once a window has been minimised to
this tag form, it no longer appears on the taskbar.
________________________________________________________________________

Requirements
¯¯¯¯¯¯¯¯¯¯¯¯
This script uses features found only in PowerPro versions v4.1 and
above.
________________________________________________________________________

Installation
¯¯¯¯¯¯¯¯¯¯¯¯
If you already have Floating Tag installed, please overwrite all files
when asked.

1. If you already have Floating Tag v1.0 installed, remove the ‘Floating
   Tag: X’ command lists from your configuration.

2. Extract FloatingTag.PowerPro to your Scripts folder, e.g.:
   C:\Program Files\PowerPro\Scripts\FloatingTag.PowerPro

3. Create a folder named FloatingTag under your Skins folder, e.g.:
   C:\Program Files\PowerPro\Skins\FloatingTag

4. Extract Back.bmp and Skin.txt to this newly created folder, e.g.:
   C:\Program Files\PowerPro\Skins\FloatingTag\Back.bmp
   C:\Program Files\PowerPro\Skins\FloatingTag\Skin.txt
________________________________________________________________________

Invoking
¯¯¯¯¯¯¯¯
Minimising a window to a tag involves a script call with a caption list
as a parameter:

.FloatingTag("Caption List")

Floating Tag will minimise the first window to match the caption list.

By setting a hotkey to invoke .FloatingTag("Active") you will be able
to minimise windows to a tag with a key press. By setting a mouse action
to invoke .FloatingTag("Under") you will be able to minimise windows
using e.g. a middle click on a window's caption.
________________________________________________________________________

Usage
¯¯¯¯¯
A tag consists of a ‘grip’ area and the tagged window's program icon.

*  Left- or middle-dragging the grip allows you to reposition the tag
   on the screen.

*  Left-clicking the icon will restore the window to its original form.

*  Middle-clicking the icon will transfer the tag to the system tray.
   This is equivalent to PowerPro's *Window TrayMin feature.

*  Right-clicking either the grip or the icon presents a popup menu that
   allows you to restore the window, transfer it to the system tray, or
   close the tag without restoring the window.

Tags will automatically disappear if their corresponding window closes
or reappears as a visible window.
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
v2.1 (5/10/2004)
*  The script no longer conforms to Standard Configuration and should
   now function without modification on any PowerPro v4.1 configuration

v2.0 (4/10/2004)
*  Modifications to the .PCF are no longer needed in order to install
  Floating Tag
*  It is now possible to minimise any amount of windows to tags, not
   just 10

v1.0 (30/11/2003)
*  Initial release
________________________________________________________________________
