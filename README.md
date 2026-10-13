# Arcade IO Emulator
**Turn your original arcade cabinet into a plug-and-play PC machine.
No crazy setup, no rewiring.**

<img width="1200" height="1200" alt="1771569479898576332006785203525" src="https://github.com/user-attachments/assets/5200769a-40d4-4a0a-a78b-dbd5e578312f" />


ArcadeIOEmulator is the easiest way to replace an original arcade PC with a modern equivalent, or just unlock your existing hardware, enabling it to play any PC, emulator or retro game. 

Acting like an all-in-one Windows driver, all controls will be available on your Windows PC as a new game controller that can be used with any emulator or game.
Force feedback is also supported, along with output lamps which use any kind of program such as Teknoparrot, outputblaster, ffbblaster, DemulShooter, supermodel, mame etc.

If you need a hand or would just like to be amongst fellow arcade enthusiasts, please visit our Discord.
https://discord.gg/CJkEJws2fN

# Support for multiple systems...

<img width="516" height="420" alt="image" src="https://github.com/user-attachments/assets/bbb9c076-ee50-46f9-bc2d-00aa54c1745f" />


- **Raw Thrills**
   - Fast and Furious Cabinets
   - Fast and Furious Drift Cabinets
   - H2 Overdrive Cabinets including ALL boards, led's etc
   - Superbikes 1 + 2 Cabinets
   - Other raw thrills Cabinets
   - Requires a USB port on the PC, and optionally a LPT port for Force Feedback
   - Setup Video: https://www.youtube.com/watch?v=3yjp-yZ1GlU

- **Golden Tee**
   - Golden Tee 2006, 2007, 2008, 2009, 2010, 2011, 2012, 2013, 2014, 2015, 2016, 2017, 2018, 2019 Cabinets. Maybe newer and older, not tested.
   - Requires a USB port on a PC

- **Global VR (Nytric Board)**
   - PGA Tour Challenge etc
   - Need for Speed
   - And many more
   - Trackball cabinets by default. Driving cabinets can use the wheel and an LPT port for force feedback
   - Requires a USB port on a PC

- **Taito x2/x3**
   - Support Fast I/O DMAC boards
   - Fast I/O microcontroller boards
   - Full setup info is shown when you fire up the app.
   - Falls back to JVS if Fast IO is not available

- **Taito Type X4**
   - Requires a USB port on a PC

- **Sega Europa-R**
   - Sega Rally 3 Cabinets
   - Sega Showdown Cabinets
   - Sega Grid Cabinets
   - Requires a USB port on a PC, and optionally a LPT port for Force Feedback
   
- **All in one JVS Support** 
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
      - Sega 838-13683 boards can also plug in over USB. Pick Sega JVS / NAOMI (WinUSB) and the app can install the driver
   - **Other JVS Boards**
      - We think this should work with many more boards also.

- **Namco USIO (System 357 / 369)**
   - USB connection to the USIO PCB. DIP switch 2 must be OFF
   - The app can install the WinUSB driver for you
   - Razing Storm light guns work by mapping vJoy in TeknoParrot
   - Full setup info is shown when you fire up the app

- **Sega IO4 (RingEdge / ALLS) (BETA)**
   - 835-15257 I/O board over a normal USB port. No extra driver
   - Wheel, light-gun, and button cabinets. Should auto detect, if not you can swap the board config type in board settings
   - Cabinet lamps are supported
   - FFB In progress


** Systems that are in beta have recently been added,if you have one, please let us know how you get on via Discord.

# Also in the app
- Rebind cabinet buttons and lamps
- Known games get their lamps mapped automatically when FFBBlaster, OutputBlaster, or DemulShooter is running. DemulShooter start, gun recoil, holder, brake, and billboard outputs light the matching cabinet lamps. If a game isn't in the list, open Outputs while it's running and bind what you see to your cabinet lamps
- Calibrate the wheel, pedals, and other controls
- JVS light guns hold the crosshair still while you aim, so you can calibrate
- H2Overdrive on a Raw Thrills board includes force feedback, cabinet lamps, and the LED speedo
- Menus and setup guides in English, French, German, and Spanish
- Optional update check when the app starts. Turn it off in General Options if the cabinet has no internet


# Super Easy Installation
1) Download the latest release here https://github.com/mightymikem/arcadeioemulator/releases
2) Follow the instructions for your cabinet/board.
3) Once done, your cabinet will appear as a new game controller you can use in any game.
4) Give it a try! Unlicensed runs last 5 minutes at a time.
5) If everything works, grab a licence at https://buymeacoffee.com/arcadeioemulator. A licence is for life for one pc, and doesnt require an internet connection :)

# Setup Videos
- Raw Thrills: https://www.youtube.com/watch?v=3yjp-yZ1GlU

# Got a machine we haven't supported?
If you have a machine that needs IO working with modern pc's, let us know! We'd love to add support. Hop on our Discord server and let us know (link above)

# Special Thanks and acknowledgements
- Corey Griffith and Joseph Howse for their Taito FastIO implementation https://github.com/JoeHowse/FastIO2KB.
- Benjamin Maurin for his incredible VjoyIoFeeder project https://github.com/njz3/vJoyIOFeederWithFFB.
- argonlefou for DemulShooter https://github.com/argonlefou/DemulShooter.

