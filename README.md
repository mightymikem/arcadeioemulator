# Arcade IO Emulator
Allowing original arcade IO hardware such as controls, lamps and force feedback to be used with any PC.
All controls will be available on your PC as a new game controller that can be used with any emulator or game.
Force feedback is also emulated, along with output lamps which use any kind of output program such as mamehooker, outputblaster, etc.

If you need a hand, or would just like to be amongst fellow arcade enthusiasts please visit our discord
https://discord.gg/CJkEJws2fN

Currently supported hardware
- Fast and Furious
- Fast and Furious Drift
- H2 Overdrive
- Other raw thrills cabinets
- **BETA** Golden Tee Nitehawk based cabinets (Maybe more, ive not tested)
- **BETA** Europa-R. BETA. Sega Rally 3, Showdown, Grid.
- **BETA** Namco JVS (ES3, maybe others)

# Installation guide
1) Download and install the latest version of vJoy https://github.com/shauleiz/vJoy/releases
2) Download and install the latest version of .net https://dotnet.microsoft.com/en-us/download
3) Once installed load the vJoy configuration program. Select the first controller and then make sure only the following options are ticked
   a) Axes - X, Z and Ry
   b) Number of buttons - 16
   c) Force feedback - Enable effects and then check all effects are enabled
4) Download the latest release from the Releases section here.
5) Visit https://buymeacoffee.com/arcadeioemulator and grab a licence
6) Unzip the ArcadeIOEmulator project somewhere, and check the "board specific" instructions below...

# Board Specific Instructions
Use the following instructions based on your arcade boards...

# Raw Thrills + Sega Europa R
1) Connect the USB cable from the main IO board to your PC. It's the green one with the Jamma harness attached.
2) (Optional) Connect the LPT port from the second IO board (Usually seated below the Jamma board) to your PC if you have an LPT port on your PC. Ideally your motherboard has a built in LPT port, otherwise support can be spotty for generic cards) Everything will work fine without this, but you won't get Force Feedback.
3) (Optional) If you have connected the LPT port above, make sure the port is running on PORT 0378 - 037F if possible, if not its should still work. You may need to do this in device manager, or bios, or both. Some users have also reported changing the LPT port to LPT3 seems to fix issues with external LPT cards etc.

# Golden Tee
1) Connect the USB cable from the main IO board to your PC.

We will be updating this project regularily, so please check back for updates!

# Got a machine we havent supported?
if you have a machine that needs IO working with modern pcs let us know! We'd love to add support. 

# Want to contribute?
If you have experience in reverse engineering arcade IO, we'd love you to get involved.
We're looking to add as many IO board emulations as possible, just drop us a line!

