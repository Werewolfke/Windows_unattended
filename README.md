# Windows_unattended
These are just Unattended files for windows.
They 
Bypass tpm, cpu and ram requirements (for win11)
Make a 'User' without password
Debloat without stripping safety features
Auto install chrome (as normally edge should be deleted but as it works like a virus, it somehow always comes back.)

Note; there is no real scripting done this is a pure unattended file with the only powershell beeing the one-liner to install Chrome, and the uninstalling from the windows packets.
This is all visible in the xml that is easy to read, even for someone without coding experience.

How to;
Rename the xml file to the name is 'autounattend.xml' (i made it easy, delete all characters behind it.)
either on the usb u created to install windows with, u drag the xml file to the root of the usb. (means the place u see when u open the usb.)
Or if u want it as a iso, use 'Anyburn', and click 'edit image file', and add the file the same way.

There are 10 files each have their own setup process, read the name to see;
There are ones that install 'pro' adn there are that install the 'home' version of windows.

Then comes the language, they all install in english but have u either manually choose it at setup, select US automatically or choose BE (belgium) automatically.
Ofcourse u can adjust this when windows is booted.

The last part is how it devides the disk... if u have a disk that is allowed to be wiped fully, use 'AutoDiskpart'
If u have multiple drives, and have other data use the 'OwnDiskPart' version.
