# Arcade IO Emulator
**Turn your original arcade cabinet into a plug-and-play PC machine.
No crazy setup, no rewiring.**

<img width="1481" height="857" alt="image" src="https://github.com/user-attachments/assets/a15dfca3-4d69-4d6b-a15a-c674e923c0ae" />


ArcadeIOEmulator is the easiest way to replace an original arcade PC with a modern equivalent, or just unlock your existing hardware, enabling it to play any PC, emulator or retro game. 

Acting like an all-in-one Windows driver, all controls will be available on your Windows PC as a new game controller that can be used with any emulator or game.
Force feedback is also supported, along with output lamps which use any kind of program such as Teknoparrot, outputblaster, ffbblaster, DemulShooter, supermodel, mame etc.

If you need a hand or would just like to be amongst fellow arcade enthusiasts, please visit our Discord.
https://discord.gg/CJkEJws2fN

# Support for multiple systems...

<img width="832" height="662" alt="image" src="https://github.com/user-attachments/assets/2cd2c6c7-b5f3-4334-a397-a0bded95d22c" />


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

# Auto Outputs
<img width="667" height="361" alt="image" src="https://github.com/user-attachments/assets/58762261-f9f6-4bdc-85fc-61d953826efe" />
Automatically detects the game being played and remaps outputs so they work without any issues just as they should on your cabinet.
Works with Mame, TeknoParrot OutputBlaster and FFBBlaster, Demulshooter and more natively.
Alternatively setup your outputs per game, its your choice!

# Wheel, Lightgun and Trackball Calibration
<img width="698" height="274" alt="image" src="https://github.com/user-attachments/assets/220e389b-6bc4-4cea-8620-f26b7ce1c9d2" />
Ensure your controls are working just as they should be, no matter what state your pots are in with auto calibration for wheels, gas and brake, lightguns, trackballs and more.

# Also in the app
- Rebind cabinet buttons and lamps
- Menus and setup guides in English, French, German, and Spanish
- Auto updates if you have a web connection on your cabinet.

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

