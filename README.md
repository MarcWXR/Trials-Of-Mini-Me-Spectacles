# Trials-Of-Mini-Me-Spectacles
A working Puzzle Platformer for SnapChat Spectacles utilising the experimental Bluetooth game controller API and a modified version of the BitMoji Character Controller. The project contains a working mini game scene with 3D models, Spectacles hand interactions on platforms and scene elements.
The project is a puzzle platformer inspired by games I loved playing as a kid. The current set up is a basic time challenge to make it to the top in the fastest possible time. It starts when the player sets foot on the first platform and ends with a particle birst when the player reaches the top.

# Features
The hand interaction mechanic is very simple and I set up with wired parameters. For instance, moving a playform up and down on the Y axis controls the rotation of the balance beams. You can easily duplicate these and tweak the settings. 
There are also a few behaviours set up for starting and ending the timer (Timer Events - in the scene tree) and enabling / disabling scene elements based on proximity. (Boulder Events)
All of the scripts are commented and easy to configure because thats the way I like it! :-)

# Why
I fell in love with the Bluetooth game controller! I love playing games with a controller and I have a passion for puzzle platformers. I wanted to create a game that works in the users space in a way that felt intuitive and combined the hand interactions with a familiar platform game movement. 
The Spectacles Bitmoji Character Controller set up did not have a real jump configured, it only played the jump animation so I copied the relevent code across from the Snap Lens example project and added it to this one. Hopefully this makes it a lot easier for others to create these types of games in anticipation of the bluetooth game controller API moving from experimental status.



