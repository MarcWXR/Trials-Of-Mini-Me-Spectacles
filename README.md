# Trials-Of-Mini-Me-Spectacles
A working Puzzle Platformer for SnapChat Spectacles utilising the experimental Bluetooth game controller API and a modified version of the BitMoji Character Controller. The project contains a working mini game scene with 3D models, Spectacles hand interactions on platforms and scene elements.
The project is a puzzle platformer inspired by games I loved playing as a kid. The current set up is a basic time challenge to make it to the top in the fastest possible time. It starts when the player sets foot on the first platform and ends with a particle birst when the player reaches the top.
The hand interaction mechanic is very simple and set up with wired parameters. Moving a playform up and down on the Y axis controls the rotation of the balance beams. There are also a few behaviours set up for starting and ending the timer and enabling / disabling scene elements based on proximity.
The Spectacles Bitmoji Character Controller set up did not have a real jump configured, it only played the jump animation so I copied the relevent code across from the Snap Lens example project and added it to this one.
All of the scripts are commented and easy to configure. 
