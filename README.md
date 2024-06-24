# Arcade IO Emulator
Allowing original arcade IO hardware to be used with any PC.
All controls will be available on your PC as a new game controller that can be used with any emulator or game.
Force feedback is also emulated, along with output lamps which use any kind of output program such as mamehooker, outputblaster, etc.

Currently supported hardware
- Fast and Furious
- Fast and Furious Drift
- H2 Overdrive

# Installation guide
1) Download and install the latest version of vJoy https://github.com/shauleiz/vJoy/releases
2) Once installed load the vJoy configuration program. Select the first controller and then make sure only the following options are ticked
   a) Axes - X, Z and Ry
   b) Number of buttons - 16
   c) Force feedback - Enable effects and then check all effects are enabled
3) Now unzip the ArcadeIOEmulator project somewhere, and check the "board specific" instructions below...

# Board Specific Instructions
Use the following instructions based on your arcade boards...

# Raw Thrills (FnF, Drive and H2 Overdrive)
1) Connect the USB cable from the main IO board to your PC. It's the green one with the Jamma harness attached.
2) (Optional) Connect the LPT port from the second IO board (Usually seated below the Jamma board) to your PC if you have an LPT port on your PC. Everything will work fine without this, but you won't get Force Feedback.
3) (Optional) If you have connected the LPT port above, make sure the port is running on PORT 0378 - 037F. You may need to do this in device manager, or bios, or both.

We will be updating this project regularily, so please check back for updates!

# Want to contribute?
If you have experience in reverse engineering arcade IO, we'd love you to get involved.
We're looking to add as many IO board emulations as possible, just drop us a line!
