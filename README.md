# Resident Evil: Code: Veronica Door Skip

This repository contains patches to remove door animations in Resident Evil/Biohazard: Code: Veronica for PlayStation 2 and PlayStation 3 releases running on console or emulator.

# Installation

## PlayStation 3

### RPCS3

1. Download [imported_patch.yml](https://raw.githubusercontent.com/kapdap/re-cvx-doorskip/master/RPCS3/imported_patch.yml) and save it to ***RPCS3\patches\imported_patch.yml***.
2. Open RPCS3 then ***Right Click Game***, select ***Configure Game Patches*** and enable the patch.
3. Run the game!

### Console

Install [Artemis PS3](http://artemis.psdev.tk/) onto your PS3.

1. Run Artemis, select **Online DB** and choose your release from the list:

```
[JP] Biohazard Code Veronica X          NPJB00135    01.01
     ...
[EU] Resident Evil Code Veronica X      NPEB00553    01.00
[US] Resident Evil Code Veronica X      NPUB30467    01.00
```

2. Enable ***Remove Door Animations*** code.
3. Read the [Using Artemis](http://artemis.psdev.tk/INSTALLATION.html#using-artemis) guide for more info on running the game.

Installing codes onto a USB drive (optional):

1. On a USB drive create a folder called ***USERLIST***.
2. Download the patch file for your release and save it to ***USERLIST***:
   - [[NPJB00135] [JP] Biohazard: Code: Veronica Kanzenban](https://raw.githubusercontent.com/kapdap/re-cvx-doorskip/master/NetCheat/Biohazard%20Code%20Veronica%20X%20NPJB00135%2001.01.ncl)
   - [[NPUB30467] [US] Resident Evil: Code: Veronica X HD](https://raw.githubusercontent.com/kapdap/re-cvx-doorskip/master/NetCheat/Resident%20Evil%20Code%20Veronica%20X%20NPUB30467%2001.00.ncl)
   - [[NPEB00553] [EU] Resident Evil: Code: Veronica X](https://raw.githubusercontent.com/kapdap/re-cvx-doorskip/master/NetCheat/Resident%20Evil%20Code%20Veronica%20X%20NPEB00553%2001.00.ncl)
3. Insert the USB drive into your PS3 and run Artemis.
4. Select **Cheats** and choose your release from the list.

```
[JP] Biohazard Code Veronica X          NPJB00135    01.01
     ...
[EU] Resident Evil Code Veronica X      NPEB00553    01.00
[US] Resident Evil Code Veronica X      NPUB30467    01.00
```

5. Enable ***Remove Door Animations*** code.
6. Read the [Using Artemis](http://artemis.psdev.tk/INSTALLATION.html#using-artemis) guide for more info on running the game.

## PlayStation 2

### PCSX2

1. Download the patch file for your release and save it to ***PCSX2\cheats***:
   - [[SLPM-650.22] [JP] Biohazard: Code: Veronica Kanzenban](https://raw.githubusercontent.com/kapdap/re-cvx-doorskip/master/PCSX2/d0cf2395.pnach)
   - [[SLUS-201.84] [US] Resident Evil: Code: Veronica X](https://raw.githubusercontent.com/kapdap/re-cvx-doorskip/master/PCSX2/24036809.pnach)
   - [[SLES-503.06] [EU] Resident Evil: Code: Veronica X](https://raw.githubusercontent.com/kapdap/re-cvx-doorskip/master/PCSX2/6ea9dda9.pnach)
2. Open PCSX2, select ***System*** and check ***Enable Cheats***.
3. Run the game!

### Console

Codes for Action Replay/GameShark/CodeBreaker etc...

**[SLPM-650.22] [JP] Biohazard: Code: Veronica Kanzenban**

```
0013393C 00000000
00133944 00000000
```

**[SLUS-201.84] [US] Resident Evil: Code: Veronica X**

```
00133D4C 00000000
00133D54 00000000
```

**[SLES-503.06] [EU] Resident Evil: Code: Veronica X**

```
00133FCC 00000000
00133FD4 00000000
```

## GameCube

### Dolphin

1. Download the patch file for your release and save it to ***Dolphin Emulator\GameSettings***:
   - [[GCDJ08] [JP] Biohazard: Code: Veronica Kanzenban](https://raw.githubusercontent.com/kapdap/re-cvx-doorskip/master/Dolphin/GCDJ08.ini)
2. Open Dolphin and run the game!

# Acknowledgements

 - [nolberto82](https://gamehacking.org/vb/member/600-nolberto82) - [Skip Door Transition (SLUS-201.84)](https://gamehacking.org/vb/forum/video-game-hacking-and-development/hacker-threads/4554-nolberto82-codes/page264#post152904)
 - [RyTheHexer](https://gamehacking.org/vb/member/37426-rythehexer) - [Faster Area Transition (SLES-503.06)](https://gamehacking.org/vb/forum/video-game-hacking-and-development/hacker-threads/210219-rythehexer-s-ps2-mainly-pal-new-codes#post210387)
