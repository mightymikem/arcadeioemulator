# Arcade IO Emulator
**Turn your original arcade cabinet into a plug-and-play PC machine.
No crazy setup, no rewiring.**

<img width="1200" height="1200" alt="1771569479898576332006785203525" src="https://github.com/user-attachments/assets/5200769a-40d4-4a0a-a78b-dbd5e578312f" />


ArcadeIOEmulator is the easiest way to replace an original arcade PC with a modern equivalent, or just unlock your existing hardware, enabling it to play any PC, emulator or retro game. 

Acting like an all-in-one Windows driver, all controls will be available on your Windows PC as a new game controller that can be used with any emulator or game.
Force feedback is also supported, along with output lamps which use any kind of program such as Teknoparrot, outputblaster, ffbblaster, supermodel, mame etc.

If you need a hand or would just like to be amongst fellow arcade enthusiasts, please visit our Discord.
https://discord.gg/CJkEJws2fN

# Support for lots of systems...

<img width="516" height="420" alt="image" src="https://github.com/user-attachments/assets/bbb9c076-ee50-46f9-bc2d-00aa54c1745f" />


- **Raw Thrills**
   - Fast and Furious Cabinets
   - Fast and Furious Drift Cabinets
   - H2 Overdrive Cabinets
   - Superbikes 1 + 2 Cabinets
   - Other raw thrills Cabinets
   - Requires a USB port on the PC, and optionally a LPT port for Force Feedback

- **Golden Tee**
   - Golden Tee 2006, 2007, 2008, 2009, 2010, 2011, 2012, 2013, 2014, 2015, 2016, 2017, 2018, 2019 Cabinets. Maybe newer and older, not tested.
   - Requires a USB port on a PC

- **Global VR (Nytric Board)**
   - PGA Tour Challenge etc
   - Need for Speed
   - And many more
   - Requires a USB port on a PC

- **BETA: Taito x2/x3**
   - Support Fast I/O DMAC boards
   - Fast I/O microcontroller boards
   - Full setup info is shown when you fire up the app.
   - Falls back to JVS if Fast IO is not available

- **BETA: Taito Type X4**
   - Tested with "Love Life after school activity".
   - Haven't tried others yet
   - Requires a USB port on a PC

- **BETA: Sega Europa-R**
   - Sega Rally 3 Cabinets
   - Sega Showdown Cabinets
   - Sega Grid Cabinets
   - Requires a USB port on a PC, and optionally a LPT port for Force Feedback
   
- **BETA: All in one JVS Support** 
   - Requires RS-485 → USB adapter
   - **Namco JVS Supported** 
      - Mario Kart Arcade Cabinets
      - Machstorm Cabinets
      - Star Wars Battlepod Cabinets
      - Wangan Midnight Maximum Tune 5, 5DX, 5DX PLUS, 6, 6R etc Cabinets
      - Tekken 7 Cabinets
      - Time Crisis 5 Cabinets
      - Pokken Tournament Cabinets
      - Dead Heat Cabinets
      - Many other Namco JVS Cabinets   
   - **Taito JVS Supported**
      - Chase HQ 2 Cabinets
      - D1GP Cabinets
      - Super Street Fighter 4 Cabinets
      - Many other Taito cabinets
   - **Sega JVS Supported**
      - Naomi/Naomi 2
      - Lindbergh
      - Triforce
      - RingEdge
      - etc
   - **Other JVS Boards**
      - We think this should work with many more boards also.


** Systems that are in beta have recently been added,if you have one, please let us know how you get on via Discord.

# Installation guide
1) Download the latest release here https://github.com/mightymikem/arcadeioemulator/releases
2) Once installed, your cabinet will appear as a new game controller you can use in any game.
3) Give it a try!
4) If everything works, grab a licence at https://buymeacoffee.com/arcadeioemulator


# Board Specific Instructions
Use the following instructions based on your arcade boards...

# Raw Thrills / Sega Europa R
1) Connect the USB cable from the main IO board to your PC. It's the green one with the Jamma harness attached.
2) (Optional) Connect the LPT port from the second IO board (Usually seated below the Jamma board) to your PC if you have an LPT port on your PC. Ideally, your motherboard has a built-in LPT port; support can be spotty for generic cards. Everything will work fine without this, but you won't get Force Feedback.
3) (Optional) If you have connected the LPT port above, make sure the port is running on PORT 0378 - 037F if possible; if not, it should still work. You may need to do this in Device Manager, or bios, or both. Some users have also reported that changing the LPT port to LPT3 seems to fix issues with external LPT cards, etc.

# Golden Tee
1) Connect the USB cable from the main IO board to your PC. That's it!

# JVS Boards
1) Connect the IO board cable to your RS-485 → USB adapter.
2) Plugin USB from the adapter into your PC.

We will be updating this project regularly, so please check back for updates!

# Got a machine we haven't supported?
If you have a machine that needs IO working with modern pc's, let us know! We'd love to add support. Hop on our Discord server and let us know (link above)

# Want to contribute?
If you have experience in reverse engineering arcade IO, we'd love you to get involved.
We're looking to add as many IO board emulations as possible. Just drop us a line on Discord.

# Special Thanks and acknowledgements
- Corey Griffith and Joseph Howse for their Taito FastIO implementation https://github.com/JoeHowse/FastIO2KB.
- Benjamin Maurin for his incredible VjoyIoFeeder project https://github.com/njz3/vJoyIOFeederWithFFB.

