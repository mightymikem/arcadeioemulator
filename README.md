# Arcade IO Emulator
**Allowing original arcade IO hardware, such as controls, lamps, and force feedback, to be used with any Windows PC.**

**No cutting wires, no extra controller boards, just plug the original hardware into your PC!**

ArcadeIOEmulator is the easiest way to replace a dead PC with a modern equivalent, or just unlock your existing hardware, enabling it to play thousands of games. 

Acting like an all-in-one Windows driver, all controls will be available on your Windows PC as a new game controller that can be used with any emulator or game.
Force feedback is also supported, along with output lamps which use any kind of output program such as outputblaster, ffbblaster, supermodel, mame etc.

If you need a hand or would just like to be amongst fellow arcade enthusiasts, please visit our Discord.
https://discord.gg/CJkEJws2fN

Currently supported hardware
- **Raw Thrills**
   - Fast and Furious
   - Fast and Furious Drift
   - H2 Overdrive
   - Other raw thrills cabinets
   - Requires a USB port on the PC, and optionally a LPT port for FFB

- **BETA: Golden Tee**
   - Golden Tee 2006, 2007, 2008, 2009, 2010, 2011, 2012, 2013, 2014, 2015, 2016, 2017, 2018, 2019. Maybe newer and older, not tested.
   - Requires a USB port on the PC
   
- **BETA:  Europa-R**
   - Sega Rally 3
   - Sega Showdown
   - Sega Grid
   - Requires a USB port on the PC, and optionally a LPT port for FFB
   
- **BETA: Namco JVS** (ES3, maybe others)
  - Mario Kart Arcade Cabs
  - Machstorm
  - Star Wars Battlepod
  - Wangan Midnight Maximum Tune 5, 5DX, 5DX PLUS, 6, 6R etc
  - Tekken 7
  - Time Crisis 5
  - Pokken Tournament
  - Other Namco JVS Cabinets
  - Requires RS-485 → USB adapter
 
- **BETA: Taito Type X2**
   - Chase HQ 2
   - D1GP
   - Super Street Fighter 4
   - And probably all other Taito Type X2 games

# Installation guide
1) Download the latest release here https://github.com/mightymikem/arcadeioemulator/releases
2) The program will guide you through installing prerequisites.
3) Once everything's installed, you will have vJoy. Load the vJoy configuration program. Select the first controller and then make sure only the following options are ticked
   a) Axes - X, Z, and Ry
   b) Number of buttons - 16
   c) Force feedback - Enable effects and then check all effects are enabled
5) Visit https://buymeacoffee.com/arcadeioemulator and grab a licence

# Board Specific Instructions
Use the following instructions based on your arcade boards...

# Raw Thrills / Sega Europa R
1) Connect the USB cable from the main IO board to your PC. It's the green one with the Jamma harness attached.
2) (Optional) Connect the LPT port from the second IO board (Usually seated below the Jamma board) to your PC if you have an LPT port on your PC. Ideally, your motherboard has a built-in LPT port; support can be spotty for generic cards. Everything will work fine without this, but you won't get Force Feedback.
3) (Optional) If you have connected the LPT port above, make sure the port is running on PORT 0378 - 037F if possible; if not, it should still work. You may need to do this in Device Manager, or bios, or both. Some users have also reported that changing the LPT port to LPT3 seems to fix issues with external LPT cards, etc.

# Golden Tee
1) Connect the USB cable from the main IO board to your PC. That's it!

# Namco JVS / Taito Type X2
1) Connect the IO board cable to your RS-485 → USB adapter.
2) Plugin USB from the adapter into your PC.

We will be updating this project regularly, so please check back for updates!

# Got a machine we haven't supported?
If you have a machine that needs IO working with modern pc's, let us know! We'd love to add support. Hop on our Discord server and let us know (link above)

# Want to contribute?
If you have experience in reverse engineering arcade IO, we'd love you to get involved.
We're looking to add as many IO board emulations as possible. Just drop us a line on Discord.

