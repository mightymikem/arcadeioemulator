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

<img width="856" height="708" alt="image" src="https://github.com/user-attachments/assets/334683d6-747c-46ba-968f-8096cf478c30" />


- **Raw Thrills**
   - USB I/O cabinets:
     - The Fast and the Furious
     - The Fast and the Furious: Drift
     - Fast & Furious SuperCars
     - Super Bikes, Super Bikes 2
     - H2Overdrive (including the lamp and LED boards)
     - Dirty Drivin'
     - Nicktoons Nitro
   - Requires a USB port on the PC, and optionally a LPT port for Force Feedback
   - Setup Video: https://www.youtube.com/watch?v=3yjp-yZ1GlU

- **Golden Tee**
   - Incredible Technologies Golden Tee cabinets:
     - 2006
     - 2007
     - 2008
     - 2009
     - 2010
     - 2011
     - 2012
     - 2013
     - 2014
     - 2015
     - 2016
     - 2017
     - 2018
     - 2019
   - Newer and older years are not tested.
   - Requires a USB port on a PC

- **Global VR (Nytric Board)**
   - Nytric USB I/O cabinets:
     - EA Sports PGA Tour Golf
     - PGA Tour Golf Championship II
     - PGA Tour Golf Championship III
     - PGA Tour Golf Challenge Edition
     - PGA Tour Golf Team Challenge
     - Need for Speed Underground
     - Need for Speed GT
     - Need for Speed Carbon upgrade cabinets
     - EA Sports Madden Football (2-player)
   - Dedicated Carbon cabinets use a different GVRI/O board
   - Trackball cabinets by default. Driving cabinets can use the wheel and an LPT port for force feedback
   - Requires a USB port on a PC

- **Taito Type X2 / X3 (Fast I/O)**
   - Fast I/O DMAC cabinets:
     - Dariusburst: Another Chronicle
     - Dariusburst: Another Chronicle EX
     - NESiCAxLive Type X2 machines
   - Type X3 cabinets:
     - Gyrozetter
     - Gunslinger Stratos
     - Gunslinger Stratos 2
     - Gunslinger Stratos 3
     - Left 4 Dead: Survivors
     - Lord of Vermilion III
     - Lord of Vermilion IV
     - Ultra Street Fighter IV
     - Theatrhythm Final Fantasy: All-Star Carnival
     - School of Ragnarok
     - BlazBlue: Cross Tag Battle
     - Fighting EX Layer
     - The King of Fighters XIV
     - Samurai Shodown (2019)
   - Full setup info is shown when you fire up the app
   - Falls back to JVS if Fast I/O is not available

- **Taito Type X4**
   - Type X4 cabinets:
     - Densha de Go!!
     - Love Live! School Idol Festival: After School Activity
     - Love Live! School Idol Festival: After School Activity Next Stage
     - Magicians Dead
     - Magicians Dead Next Blazing
     - Starwing Paradox
     - Street Fighter V: Type Arcade
     - Street Fighter 6: Type Arcade
   - Requires a USB port on a PC

- **Sega Europa-R**
   - Europa-R cabinets:
     - Sega Rally 3
     - GRID
     - Showdown
   - Requires a USB port on the PC
   - Requires parallel port for FFB (Uses FFB Board 838-15069)
   
- **All in one JVS Support** 
   - Requires RS-485 → USB adapter
   - **Namco JVS Supported** 
      - Mario Kart Arcade GP
      - Mach Storm
      - Star Wars: Battle Pod
      - Wangan Midnight Maximum Tune 5
      - Wangan Midnight Maximum Tune 5DX
      - Wangan Midnight Maximum Tune 5DX+
      - Wangan Midnight Maximum Tune 6
      - Wangan Midnight Maximum Tune 6R
      - Tekken 7
      - Time Crisis 5
      - Pokken Tournament
      - Dead Heat
      - Other Namco cabinets that use a JVS I/O board. System 357 and 369 cabinets use the USIO board below instead
   - **Taito JVS Supported**
      - Chase H.Q. 2
      - D1GP
      - Street Fighter IV
      - Super Street Fighter IV
      - The King of Fighters XII
      - The King of Fighters XIII
      - BlazBlue
      - Wacky Races
      - Elevator Action Death Parade
      - Haunted Museum
      - Other Type X2 cabinets wired to a JVS I/O board. Cabinets with the Fast I/O card use the Type X2 / X3 option above
   - **Sega JVS Supported**
      - Naomi and Naomi 2, including the 838-13683 USB board:
        - Crazy Taxi
        - The House of the Dead 2
        - Virtua Tennis
        - Virtua Fighter 4
        - Marvel vs. Capcom 2
        - Initial D Arcade Stage
        - OutRun 2
        - Confidential Mission
        - The Typing of the Dead
      - Triforce:
        - F-Zero AX
      - Lindbergh:
        - OutRun 2 SP
        - Virtua Fighter 5
        - Virtua Tennis 3
        - The House of the Dead 4
        - Initial D Arcade Stage 4
        - Initial D Arcade Stage 5
        - Let's Go Jungle
        - Sega Race TV
        - R-Tuned
        - Hummer
        - Hummer Extreme
      - RingEdge cabinets with the older JVS I/O board:
        - Border Break
        - After Burner Climax
        - Hatsune Miku: Project DIVA Arcade
        - Virtua Tennis 4
        - Let's Go Island 3D
        - Initial D Arcade Stage 6 AA
        - Initial D Arcade Stage 7 AAX
        - Initial D Arcade Stage 8 Infinity
        - Operation G.H.O.S.T.
        - Transformers: Human Alliance
      - Sega 838-13683 boards can also plug in over USB. Pick Sega JVS / NAOMI (WinUSB) and the app can install the driver
   - **Other JVS Boards**
      - Other cabinets that speak JVS should work too

- **Namco USIO (System 357 / 369)**
   - System 357 / 369 cabinets:
     - Tekken 6
     - Tekken 6: Bloodline Rebellion
     - Tekken Tag Tournament 2
     - Tekken Tag Tournament 2 Unlimited
     - Razing Storm
     - Deadstorm Pirates
     - Deadstorm Pirates Special Edition
     - Dark Escape 3D
     - Dark Escape 4D
     - Dragon Ball Zenkai Battle Royale
     - Gundam: Extreme Vs.
     - Gundam: Extreme Vs. Full Boost
     - Gundam: Extreme Vs. Maxi Boost
     - Taiko no Tatsujin
     - Sailor Zombie
   - USB connection to the USIO PCB. DIP switch 2 must be OFF
   - The app can install the WinUSB driver for you
   - Razing Storm light guns work by mapping vJoy in TeknoParrot
   - Full setup info is shown when you fire up the app

- **Sega IO4 (ALLS) (BETA)**
   - 835-15257 USB I/O board. No extra driver. This is the ALLS cabinet I/O.
   - ALLS cabinets:
     - House of the Dead: Scarlet Dawn
     - Fate/Grand Order Arcade
     - maimai DX
     - CHUNITHM SUPERSTAR
     - CHUNITHM NEW, and later ALLS versions
     - Ongeki
     - Sega World Drivers Championship
     - Soul Reverse
     - Puyo Puyo eSports
     - Virtua Fighter 5 Ultimate Showdown
     - Dead or Alive 6
     - Mario & Sonic at the Olympic Games Tokyo 2020 Arcade Edition
     - WCCF Footista
   - Wheel, light-gun, and button cabinets. Should auto detect, if not you can swap the board config type in board settings
   - Cabinet lamps are supported
   - FFB: Sega 838-15069 drive board fully supported

- **Konami BIO2 (BETA)**
   - Konami BIO2 USB board. Windows already has the COM port driver, so nothing extra to install
   - beatmania IIDX cabinets from IIDX 25 onward. Keys, turntables, sliders, start and effect buttons, and cabinet lamps
   - Sound Voltex cabinets from Vivid Wave onward. Buttons, knobs, and button lamps. Choose Sound Voltex in the board options. IIDX is the default
   - Requires COM port. You can change com port in bio2.ini if needed

- **Konami KFCA (BETA)**
   - Sound Voltex cabinets before Vivid Wave. Supports Buttons, knobs, volume and button lamps:
     - SOUND VOLTEX BOOTH
     - SOUND VOLTEX II -infinite infection-
     - SOUND VOLTEX III GRAVITY WARS
     - SOUND VOLTEX IV HEAVENLY HAVEN
   - Requires COM port.

- **Konami P3IO (BETA)**
   - Konami P3IO for Dance Dance Revolution. Works with no konami driver, or with it also if you have it
   - Dance Dance Revolution cabinets that use the P3IO. 
   - Both players' pads, start, and menu buttons supported
   - OPTIONAL: Pad arrow lights and bass neons use the EXTIO COM port in P3IO Options.

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
- djhackersdev for the bemanitools BIO2 protocol reference https://github.com/djhackersdev/bemanitools.

