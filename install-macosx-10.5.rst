
James Newlin (newlin83@gmail.com) was able to backport this service to Mac OS X 10.5 (Leopard).  Here are his installation and usage instructions.


Installing SoX
==============

1. Download SoX version 14.3.0 under the sox-macosx folder at http://sourceforge.net/projects/sox/files/

2. Double-click the sox-14.3.0-macosx.zip to decompress the file

3. Drag and drop the new "sox-14.3.0" folder into the Applications folder

4. Register as a Mac Developer for free at http://developer.apple.com/programs/register/

5. Sign in to http://connect.apple.com

6. Under downloads on the right hand side, click Developer Tools

7. Search the page for 3.1.4 and then download and install Xcode 3.1.4


Installing the Convert Audio Service Workflow
=============================================

1. Open "Convert sample rate and resolution.workflow" with Automator.app

2. Edit line 5 of the AppleScript.  Change::

       property sox : "sox"

   to::

        property sox : "/Applications/sox-14.3.0/sox"

3. In the *File* menu, select *Save as Plug-in* with *Plug-in for Finder*

4. Name the plug-in "Convert Audio" (or whatever else you want to use)


Usage
=====

1. In the Finder, right-click on any wav file and select *More* > *Automator* > *Convert Audio*

