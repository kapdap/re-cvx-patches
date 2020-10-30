# Resident Evil: Code: Veronica Door Skip

This repository contains patches to remove door animations in 
Resident Evil/Biohazard: Code: Veronica for PlayStation 2 and
PlayStation 3 releases running on emulator or console.

# Installation

## PlayStation 3

### RPCS3

 1. Download [RPCS3\imported_patch.yml](https://raw.githubusercontent.com/kapdap/re-cvx-doorskip/master/RPCS3/imported_patch.yml) and save to ***RPCS3\patches\imported_patch.yml***.
 2. Open RPCS3 then ***Right Click Game***, select ***Configure Game Patches*** and enable the patch.
 3. Run the game!

### Console

 1. Install [ArtemisPS3](http://artemis.psdev.tk/) onto a jailbroken PS3.
 2. On a USB stick create a folder called ***USERLIST***.
 3. Download the patch file for your release and save it to ***USERLIST***
    - [[NPJB00135] [JP] Biohazard: Code: Veronica Kanzenban](https://raw.githubusercontent.com/kapdap/re-cvx-doorskip/master/NetCheat/NPJB00135.ncl)
    - [[NPUB30467] [US] Resident Evil: Code: Veronica X HD](https://raw.githubusercontent.com/kapdap/re-cvx-doorskip/master/NetCheat/NPUB30467.ncl)
    - [[NPEB00553] [EU] Resident Evil: Code: Veronica X](https://raw.githubusercontent.com/kapdap/re-cvx-doorskip/master/NetCheat/NPEB00553.ncl)
 4. *ToDo*

## PlayStation 2

### PCSX2

 1. Download the patch file for your release and save it to ***PCSX2\Cheats***
    - [[SLPM-650.22] [JP] Biohazard: Code: Veronica Kanzenban](https://raw.githubusercontent.com/kapdap/re-cvx-doorskip/master/PCSX2/d0cf2395.pnach)
    - [[SLUS-201.84] [US] Resident Evil: Code: Veronica X](https://raw.githubusercontent.com/kapdap/re-cvx-doorskip/master/PCSX2/24036809.pnach)
    - [[SLES-503.06] [EU] Resident Evil: Code: Veronica X](https://raw.githubusercontent.com/kapdap/re-cvx-doorskip/master/PCSX2/6ea9dda9.pnach)
 2. Open PCSX2 the select ***System*** and check ***Enable Cheats***.
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

# Acknowledgements

 - [nolberto82](https://gamehacking.org/vb/member/600-nolberto82) - [Skip Door Transition (SLUS-201.84)](https://gamehacking.org/vb/forum/video-game-hacking-and-development/hacker-threads/4554-nolberto82-codes/page264#post152904)
 - [RyTheHexer](https://gamehacking.org/vb/member/37426-rythehexer) - [Faster Area Transition (SLES-503.06)](https://gamehacking.org/vb/forum/video-game-hacking-and-development/hacker-threads/210219-rythehexer-s-ps2-mainly-pal-new-codes#post210387)
