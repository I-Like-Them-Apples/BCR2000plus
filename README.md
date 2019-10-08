# BCR2000plus
Behringer BCR2000 Remote Script for Ableton Live

This script adds a new remote capabilities for the Behringer BCR2000 to Ableton Live.

The default BCR2000 settings in Live only works for the first 8 channels.  This script gives a moveable box so that you can control all the channels.

The layout is as..

The bottom row of encoders control the track volumes.

The second bottom row controls Send 1

The third row controls Send 2

The rows of buttons control Mute and Record.

The top row of encoders have 4 groups of functions.  The different functions are selected by the 4 encoder group buttons.

Group 1 has encoders controlling pans, and pushbutton sets Solo.

Group 2 has device control (the blue hand) encoders and the pushbuttons select between of 8 banks device controls.  The "Edit" and "Exit" buttons also scroll through the device control banks.  The "Store" and "Learn" buttons scroll through plugins.

Group 3 has Crossfader on encoder 6, Headphones on 7 and Master Volume on 8.  The push buttons select tracks.

Group 4 has Send 3 levels and the pushbuttons stop the clips for that track.

The buttons on the lower right move the rectangle left and right, selecting a different set of 8 channels.  It is possible to control the return channels as well as the normal channels.  The two buttons above operate the Play and Stop transport.


You will need to copy the entire BCR2000plus folder to the Ableton Live remote scripts directory...

Windows: \ProgramData\Ableton\Live x.x\Resources\MIDI Remote Scripts\
This folder is hidden by default.
Mac: The Remote Script folder is inside the Ableton Live application bundle. Locate the Live application in Finder, right click on it and select "Show Package Content". Then navigate to: /Contents/App-Resources/MIDI Remote Scripts/

After you restart Live, you should see the BCR2000plus in Preferences/Link Midi/Control Surfaces.

There is file called preset.syx you need to send to your BCR2000.  Ideally you could press the "dump" button in the Live GUI but I've found it cannot transfer the whole file properly so I recommend you use the BC Manager from here.. https://mountainutilities.eu/downloads    

Because the preset uses the store and edit buttons to navigate ableton live, you will be unable to store the preset directly from the device. So the BC Manager would be needed to write this preset directly to the BCR2000. 

TODO: Edit sysex to have save command so it can be loaded from any sysex program. 



This script is based on the https://github.com/j74/Generic-Python-Remote-Script by Fabrizio Poce
